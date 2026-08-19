# Scripts para Tampermonkey

Coleção de scripts para Tampermonkey que adicionam e modificam algumas funcionalidades no cliente web.

Os scripts devem ser instalados no **Tampermonkey** e posteriormente ativados no navegador.

**Estado em 18/08/2026:** todas as funcionalidades apresentadas neste README estão funcionais.

---

## Contador de Diamantes

Adiciona um contador de 1 hora para saber quando será possível receber novamente os diamantes.

<img width="253" height="39" alt="Contador de diamantes" src="https://github.com/user-attachments/assets/c7cf8cff-c380-424e-82cd-0293c7956321" />

---

## Ocultar Balão de Digitação

<table>
<tr>
<td valign="middle"><img width="253" height="31" alt="Ocultar balão de digitação" src="https://github.com/user-attachments/assets/46797922-b776-4ce4-98ea-e2b06649c270" /></td>
<td valign="middle">Oculta o balão que indica aos restantes utilizadores que o próprio está a escrever uma mensagem.</td>
</tr>
</table>

---

## Sniffar Opcodes

<table>
<tr>
<td valign="middle"><img width="253" height="69" alt="Sniffar Opcodes" src="https://github.com/user-attachments/assets/53a35c11-0db9-4945-bcbf-31f20055310a" /></td>
<td valign="middle">Adiciona um sniffer de opcodes que regista o tráfego trocado com o cliente, permitindo acompanhar os pacotes enviados/recebidos através da consola do navegador.</td>
</tr>
</table>

---

## Mutar Todos com Exceções

<table>
<tr>
<td valign="middle"><img width="253" height="116" alt="Mutar Todos com Exceções" src="https://github.com/user-attachments/assets/c5f24cc4-dfc8-406d-9d5d-6696c7a5e047" /></td>
<td valign="middle">

Adiciona uma opção para mutar todos os utilizadores da sala, permitindo definir exceções para determinados utilizadores.

É possível:
* Mutar todos os utilizadores da sala.
* Adicionar utilizadores à lista de exceções.
* Manter determinados utilizadores sem mute através das exceções.
* Aplicar o mute ao próprio utilizador.

</td>
</tr>
</table>

---

## Beijar Infinitamente

<table>
<tr>
<td valign="middle"><img width="253" height="31" alt="Beijar Infinitamente" src="https://github.com/user-attachments/assets/c02aeaca-59b2-4928-802d-ef93d2da85a7" /></td>
<td valign="middle">Permite enviar o beijo de forma contínua, sem necessidade de repetir a ação manualmente.</td>
</tr>
</table>

---

## Anti Ausente

<table>
<tr>
<td valign="middle"><img width="253" height="31" alt="Anti Ausente" src="https://github.com/user-attachments/assets/a0a88625-0311-428f-aa1e-65dd3b60861b" /></td>
<td valign="middle">Bloqueia a atribuição automática do estado de "ausente" ao utilizador.</td>
</tr>
</table>

---

## Enables

<table>
<tr>
<td valign="middle"><img width="253" height="31" alt="Enables" src="https://github.com/user-attachments/assets/1d1f3c4a-482f-401b-a951-a5cac36724b4" /></td>
<td valign="middle">Aplica um enable aleatório ao utilizador a cada 2 segundos.</td>
</tr>
</table>

---

## Menu Raros // Feira-Livre

O Menu Rares conta com uma nova opção para pesquisar e consultar os valores dos raros.

Ao iniciar o script, é ativado automaticamente um timer.

O processo de carregamento pode ser acompanhado através da consola do navegador.

<img width="586" height="168" alt="Timer automático" src="https://github.com/user-attachments/assets/195c5e44-ba9f-4cad-9774-b799e0cd83b1" />

Após a ativação, é também disponibilizado um campo para pesquisar o valor dos raros.

<img width="244" height="222" alt="Pesquisa de valores" src="https://github.com/user-attachments/assets/bb8b9210-b68a-48df-a71d-00662385af01" />

---

## Comparação de Preços

A Feira-Livre apresenta agora uma comparação entre o preço de venda e o valor do raro.

A diferença é apresentada através de cores:

| Cor      | Seta | Significado                            |
| -------- | :--: | --------------------------------------- |
| Vermelho | ⬆️   | Preço de venda acima do valor do raro  |
| Verde    | ⬇️   | Preço de venda abaixo do valor do raro |
| Cinza    | ➡️   | Preço de venda igual ao valor do raro  |

<img width="389" height="615" alt="image" src="https://github.com/user-attachments/assets/317d7cac-acaf-4f59-912d-3113abe1847c" />

---

## Notas

* Os scripts devem ser executados através do Tampermonkey.
* Algumas funcionalidades dependem da estrutura atual do cliente web.
* Alterações futuras no site podem exigir atualizações nos scripts.
* Para informações mais detalhadas sobre cada script, consultar os comentários existentes no respetivo código.
