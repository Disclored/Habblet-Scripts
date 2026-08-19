# Scripts para Tampermonkey

Coleção de scripts para Tampermonkey que adicionam e modificam algumas funcionalidades no cliente web.

Os scripts devem ser instalados no **Tampermonkey** e posteriormente ativados no navegador.

**Estado em 18/08/2026:** todas as funcionalidades descritas neste README encontram-se funcionais.

---

## Funcionalidades

<table>
<tr>
<td width="270" valign="top">
<img width="253" src="https://github.com/user-attachments/assets/c7cf8cff-c380-424e-82cd-0293c7956321" alt="Contador de diamantes" />
</td>
<td valign="top">

### Contador de Diamantes

Adiciona um contador de 1 hora para saber quando será possível receber novamente os diamantes.

</td>
</tr>

<tr>
<td width="270" valign="top">
<img width="253" src="https://github.com/user-attachments/assets/46797922-b776-4ce4-98ea-e2b06649c270" alt="Ocultar balão de digitação" />
</td>
<td valign="top">

### Ocultar Balão de Digitação

Oculta o balão que indica aos restantes utilizadores que o próprio está a escrever uma mensagem.

</td>
</tr>

<tr>
<td width="270" valign="top">
<img width="253" src="https://github.com/user-attachments/assets/53a35c11-0db9-4945-bcbf-31f20055310a" alt="Sniffar Opcodes" />
</td>
<td valign="top">

### Sniffar Opcodes

Adiciona um sniffer de opcodes que regista o tráfego trocado com o cliente, permitindo acompanhar os pacotes enviados e recebidos através da consola do navegador.

</td>
</tr>

<tr>
<td width="270" valign="top">
<img width="253" src="https://github.com/user-attachments/assets/c5f24cc4-dfc8-406d-9d5d-6696c7a5e047" alt="Mutar Todos com Exceções" />
</td>
<td valign="top">

### Mutar Todos com Exceções

Permite mutar todos os utilizadores da sala e definir exceções para determinados utilizadores.

É possível:

* Mutar todos os utilizadores da sala.
* Adicionar utilizadores à lista de exceções.
* Manter determinados utilizadores sem mute através das exceções.
* Aplicar o mute ao próprio utilizador.

</td>
</tr>

<tr>
<td width="270" valign="top">
<img width="253" src="https://github.com/user-attachments/assets/c02aeaca-59b2-4928-802d-ef93d2da85a7" alt="Beijar Infinitamente" />
</td>
<td valign="top">

### Beijar Infinitamente

Permite enviar o beijo de forma contínua, sem necessidade de repetir a ação manualmente.

</td>
</tr>

<tr>
<td width="270" valign="top">
<img width="253" src="https://github.com/user-attachments/assets/a0a88625-0311-428f-aa1e-65dd3b60861b" alt="Anti Ausente" />
</td>
<td valign="top">

### Anti Ausente

Bloqueia a atribuição automática do estado de "ausente" ao utilizador.

</td>
</tr>

<tr>
<td width="270" valign="top">
<img width="253" src="https://github.com/user-attachments/assets/1d1f3c4a-482f-401b-a951-a5cac36724b4" alt="Enables" />
</td>
<td valign="top">

### Enables

Aplica um enable aleatório ao utilizador a cada 2 segundos.

</td>
</tr>

<tr>
<td width="270" valign="top">
<img width="253" src="https://github.com/user-attachments/assets/f4abc006-19b4-4154-951f-b58253d2210f" alt="Timer automático da Feira-Livre" />
</td>
<td valign="top">

### Menu Raros // Feira-Livre

O Menu Rares conta com uma nova opção para pesquisar e consultar os valores dos raros.

Ao iniciar o script, é ativado automaticamente um timer.

O processo de carregamento pode ser acompanhado através da consola do navegador.

</td>
</tr>

<tr>
<td width="270" valign="top">
<img width="253" src="https://github.com/user-attachments/assets/bb8b9210-b68a-48df-a71d-00662385af01" alt="Pesquisa de valores dos raros" />
</td>
<td valign="top">

### Pesquisa de Valores

Após a ativação, é também disponibilizado um campo para pesquisar o valor dos raros.

</td>
</tr>

</table>

---

## Comparação de Preços

A Feira-Livre apresenta agora uma comparação entre o preço de venda e o valor do raro.

A diferença é apresentada através de cores:

| Cor      | Seta | Significado                            |
| :------- | :--: | :------------------------------------- |
| Vermelho |  ⬆️  | Preço de venda acima do valor do raro  |
| Verde    |  ⬇️  | Preço de venda abaixo do valor do raro |
| Cinza    |  ➡️  | Preço de venda igual ao valor do raro  |

<p align="center">
<img width="389" alt="Comparação de preços" src="https://github.com/user-attachments/assets/317d7cac-acaf-4f59-912d-3113abe1847c" />
</p>

---

## Notas

* Os scripts devem ser executados através do Tampermonkey.
* Algumas funcionalidades dependem da estrutura atual do cliente web.
* Alterações futuras no site podem exigir atualizações nos scripts.
* Para informações mais detalhadas sobre cada script, consultar os comentários existentes no respetivo código.
