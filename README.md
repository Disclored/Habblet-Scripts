# Scripts para Tampermonkey

Coleção de scripts para Tampermonkey que adicionam e modificam algumas funcionalidades no cliente web.

Os scripts devem ser instalados no **Tampermonkey** e posteriormente ativados no navegador.

**Estado em 18/08/2026:** todas as funcionalidades apresentadas neste README estão funcionais.

Além deste README, cada script contém comentários no próprio código com uma explicação mais detalhada sobre o seu funcionamento.

---

## Contador de Diamantes

Adiciona um contador de 1 hora para saber quando será possível receber novamente os diamantes.

<img width="253" height="39" alt="Contador de diamantes" src="https://github.com/user-attachments/assets/c7cf8cff-c380-424e-82cd-0293c7956321" />

---

## Mutar Todos com Exceções

Adiciona uma opção para mutar todos os utilizadores da sala, permitindo definir exceções para determinados utilizadores.

É possível:

* Mutar todos os utilizadores da sala.
* Adicionar utilizadores à lista de exceções.
* Manter determinados utilizadores sem mute através das exceções.
* Aplicar o mute ao próprio utilizador.

<img width="253" height="120" alt="image" src="https://github.com/user-attachments/assets/fdb928c1-7ff5-45e4-afee-a00884a31f0f" />


A lista de utilizadores mutados e não mutados também pode ser consultada através da consola do navegador.

### Utilizadores mutados

<img width="750" height="528" alt="image" src="https://github.com/user-attachments/assets/f86ce648-db3b-4f3b-9ebf-e458fb5cfdaa" />


### Utilizadores não mutados

<img width="359" height="38" alt="Utilizadores não mutados" src="https://github.com/user-attachments/assets/7cdebc67-aac5-4a06-a53c-64c8da029501" />

---

## Menu Rares — Feira-Livre

O Menu Rares conta com uma nova opção para pesquisar e consultar os valores dos raros.

<img width="253" height="546" alt="Menu Rares — Feira-Livre" src="https://github.com/user-attachments/assets/f6a8f2bc-8cbe-4ac6-9612-cb2ec3f8de9b" />

---

## Timer Automático

Ao iniciar o script, é ativado automaticamente um timer.

O processo de carregamento pode ser acompanhado através da consola do navegador.

<img width="586" height="168" alt="Timer automático" src="https://github.com/user-attachments/assets/195c5e44-ba9f-4cad-9774-b799e0cd83b1" />

Após a ativação, é também disponibilizado um campo para pesquisar o valor dos raros.

<img width="244" height="222" alt="Pesquisa de valores" src="https://github.com/user-attachments/assets/bb8b9210-b68a-48df-a71d-00662385af01" />

---

## Comparação de Preços

A Feira-Livre apresenta agora uma comparação entre o preço de venda e o valor do raro.

A diferença é apresentada através de cores:

| Cor      | Significado                            |
| -------- | -------------------------------------- |
| Vermelho | Preço de venda acima do valor do raro  |
| Verde    | Preço de venda abaixo do valor do raro |
| Cinza    | Preço de venda igual ao valor do raro  |

<img width="750" alt="Comparação de preços" src="https://github.com/user-attachments/assets/53ba2ef3-92d3-4f65-b16e-39234f20802e" />

---

## Estado

| Funcionalidade           | Estado    |
| ------------------------ | --------- |
| Contador de Diamantes    | Funcional |
| Mutar Todos com Exceções | Funcional |
| Menu Rares — Feira-Livre | Funcional |
| Timer Automático         | Funcional |
| Comparação de Preços     | Funcional |

**Última verificação:** 18/08/2026

---

## Notas

* Os scripts devem ser executados através do Tampermonkey.
* Algumas funcionalidades dependem da estrutura atual do cliente web.
* Alterações futuras no site podem exigir atualizações nos scripts.
* Para informações mais detalhadas sobre cada script, consultar os comentários existentes no respetivo código.
