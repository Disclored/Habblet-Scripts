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

Oculta o balão que indica aos restantes utilizadores que o próprio está a escrever uma mensagem.

<img width="253" height="39" alt="ocultar-balao" src="https://github.com/user-attachments/assets/75558abc-2a4a-4f52-aaa6-dc2783bc7ccf" />

---

## Sniffar Opcodes

Adiciona um sniffer de opcodes que regista o tráfego trocado com o cliente, permitindo acompanhar os pacotes enviados/recebidos através da consola do navegador.

<img width="253" height="46" alt="sniffar-opcodes" src="https://github.com/user-attachments/assets/7dc8f0c2-39e3-4071-81e0-2a7085092220" />

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

## Beijar Infinitamente

Permite enviar o beijo de forma contínua, sem necessidade de repetir a ação manualmente.
<img width="753" height="99" alt="anti-ausente" src="https://github.com/user-attachments/assets/2f6dff4e-6606-4f73-8c80-e69277012f8d" />

<img width="253" height="39" alt="beijar-infinitamente" src="https://github.com/user-attachments/assets/2f5e6522-642a-4e88-b309-3360a8b96dbd" />

---

## Anti Ausente

Bloqueia a atribuição automática do estado de "ausente" ao utilizador.

<img width="253" height="39" alt="anti-ausente" src="https://github.com/user-attachments/assets/6f46930e-66ee-427d-82c5-d5b49c328465" />

---

## Enables

Aplica um enable aleatório ao utilizador a cada 2 segundos.

<img width="253" height="39" alt="enables" src="https://github.com/user-attachments/assets/59cb458e-3793-4c56-90d0-ca6a064a4496" />

---

## Menu Raros // Feira-Livre

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
