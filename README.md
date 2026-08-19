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

<img width="244" height="65" alt="image" src="https://github.com/user-attachments/assets/7a1a43e7-5f53-46dd-8403-d92cdf29b089" />

---

## Sniffar Opcodes

Adiciona um sniffer de opcodes que regista o tráfego trocado com o cliente, permitindo acompanhar os pacotes enviados/recebidos através da consola do navegador.

Permite ver detalhes do pacote ao clicar. Bytes, Hexdecimal e ASCII

<img width="515" height="590" alt="image" src="https://github.com/user-attachments/assets/de22e735-1583-4786-9087-38919b3f77f2" />

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

<img width="262" height="75" alt="image" src="https://github.com/user-attachments/assets/d231e0c3-cac5-4d46-a711-0a7fd38dc7fb" />

---

## Anti Ausente

Bloqueia a atribuição automática do estado de "ausente" ao utilizador.

<img width="256" height="97" alt="image" src="https://github.com/user-attachments/assets/798bbd71-b226-4fe3-a34d-7f5829caf391" />

---

## Enables

Aplica um enable aleatório ao utilizador a cada 1 segundo.

<img width="252" height="45" alt="image" src="https://github.com/user-attachments/assets/9d1a2869-c896-4db1-a681-2d3b679c3354" />


---

## Menu Raros // Feira-Livre

O Menu Raros conta com uma nova opção para pesquisar e consultar os valores dos raros.

O processo de carregamento pode ser acompanhado através da consola do navegador.

<img width="586" height="168" alt="Timer automático" src="https://github.com/user-attachments/assets/195c5e44-ba9f-4cad-9774-b799e0cd83b1" />

Após a ativação, é também disponibilizado um campo para pesquisar o valor dos raros.

<img width="254" height="226" alt="image" src="https://github.com/user-attachments/assets/d37d5141-91e0-4c87-9290-eb0d1f8d28b4" />

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
