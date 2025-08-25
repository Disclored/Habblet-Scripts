//ESTE SCRIPT PAUSA A RADIO AUTOMATICAMENTE QUANDO SE ENTRA NO JOGO
//ELE NAO SILENCIA, POR ISSO, SE QUISEREM OUVIR RADIO NOVAMENTE, É SÓ CLICAR NO BOTAO NORMALMENTE PARA LIGAR

// ==UserScript==
// @name         Radio Pause Auto
// @namespace    zezinhoestiloso
// @version      1.2
// @description  Garante que ao entrar a rádio fique em pausa mudando o botão para "play"
// @author       zeezinhoestiloso
// @match        *://*.habblet.city/*
// @icon         https://www.google.com/s2/favicons?sz=64&domain=habblet.city
// @run-at       document-start
// @all-frames   true
// @grant        none
// ==/UserScript==

(function () {
  'use strict';

  // Parte característica do ícone "PAUSE" (duas barras) fornecido por você
  const PAUSE_PATH_SNIPPET = 'M144 479H48';

  // Evita clicar mais de uma vez por carregamento
  let alreadyApplied = false;

  // Utilitários
  const isElement = (n) => n && n.nodeType === 1;

  // Sobe alguns níveis no DOM procurando um container que tenha o slider de volume
  function hasVolumeSliderNearby(node) {
    let cur = node;
    for (let i = 0; i < 6 && cur; i++) {
      if (cur.querySelector && cur.querySelector('input[type="range"]')) return true;
      cur = cur.parentElement;
    }
    return false;
  }

  // Procura o botão correto (ícone SVG com path do "pause" + slider por perto)
  function findRadioPauseButtons(root = document) {
    const svgs = root.querySelectorAll('svg.fa-icon, svg.fa-icon.cursor-pointer');
    const matches = [];
    for (const svg of svgs) {
      const path = svg.querySelector('path');
      const d = path && path.getAttribute('d');
      if (!d) continue;
      if (d.includes(PAUSE_PATH_SNIPPET) && hasVolumeSliderNearby(svg)) {
        matches.push(svg);
      }
    }
    return matches;
  }

  function clickToPause(svg) {
    // Só executa uma vez
    if (alreadyApplied) return true;
    try {
      svg.dispatchEvent(new MouseEvent('click', { bubbles: true, cancelable: true, view: window }));
      alreadyApplied = true;
      console.log('[Habblet Rádio] Botão alternado para "play" (rádio em pausa).');
      return true;
    } catch (e) {
      console.warn('[Habblet Rádio] Falha ao clicar:', e);
      return false;
    }
  }

  function tryApply(root = document) {
    if (alreadyApplied) return true;
    const btns = findRadioPauseButtons(root);
    if (btns.length) {
      return clickToPause(btns[0]);
    }
    return false;
  }

  // --- Observadores e fallbacks ---

  // Observa o DOM inteiro para quando o player for injetado
  let observer = new MutationObserver((mutations) => {
    if (alreadyApplied) return;
    for (const m of mutations) {
      // Verifica nós adicionados e seus descendentes
      for (const node of m.addedNodes) {
        if (!isElement(node)) continue;
        if (tryApply(node)) {
          observer.disconnect();
          clearInterval(intervalId);
          return;
        }
      }
    }
  });

  // Começa a observar o mais cedo possível
  const startObserving = () => {
    try {
      observer.observe(document.documentElement || document, { childList: true, subtree: true });
    } catch {}
  };
  startObserving();

  // Intervalo de segurança (caso o observer perca algo)
  let attempts = 0;
  const intervalId = setInterval(() => {
    if (alreadyApplied || attempts++ > 80) { // ~20s (80 * 250ms)
      clearInterval(intervalId);
      if (observer) observer.disconnect();
      return;
    }
    tryApply();
  }, 250);

  // Também tenta em eventos padrão
  document.addEventListener('DOMContentLoaded', () => tryApply());
  window.addEventListener('load', () => tryApply());

})();
