# 🚀 Landing Page Interativa - Starbucks

Esse é um projeto da Landing Page Interativa da Starbucks! Um sistema visual desenvolvido com HTML, CSS e JavaScript, focado em simular uma página iicial do produto dinâmica e moderna. O projeto foi estruturado com uma clara separação de responsabilidades (estrutura, estilo e comportamento), ideal para demonstrar e praticar conceitos fundamentais do desenvolvimento web front-end, como manipulação do DOM, estilização avançada com CSS e criação de uma experiência de usuário engajadora.

### ✨ Funcionalidades Principais

O sistema proporciona uma experiência de navegação rica e interativa, incluindo:

* **Design Atraente:** Layout limpo e moderno inspirado na identidade visual da Starbucks.
* **Interatividade Total:** A página reage dinamicamente às ações do usuário.
* **Troca de Tema:** Alteração da cor de fundo principal com base no produto selecionado.
* **Troca de Produto:** Mudança da imagem do produto em destaque com um clique.
* **Feedback Visual:** Efeitos de `hover` suaves em elementos clicáveis, melhorando a usabilidade.

### 🛠️ Detalhes Técnicos e Estrutura do Código

O código é organizado em três arquivos distintos, cada um com uma responsabilidade única, o que torna o projeto coeso, de fácil manutenção e escalabilidade.

#### Arquivos Principais

**`index.html`**

É o arquivo central que define toda a estrutura e o conteúdo da página[cite: 2]. Ele contém os elementos que serão manipulados pelo JavaScript e estilizados pelo CSS.

* **Estrutura**: Organiza o conteúdo em seções semânticas, como o texto de apresentação (`.caixa-texto`), a imagem principal (`.caixa-imagem`) e o menu de seleção (`.menu`).
* **Vínculo**: Conecta os arquivos `styles.css` e `scripts.js` para que a página funcione corretamente.
* **Eventos**: Utiliza o atributo `onclick` nas imagens do menu para invocar as funções JavaScript, passando os parâmetros necessários (cor e imagem) para a troca dinâmica.

**`styles.css`**

Responsável por toda a parte visual do projeto, desde o layout geral até os mínimos detalhes de design.

* **Layout:** Utiliza **Flexbox** para alinhar e distribuir os elementos de forma eficiente na tela.
* **Estilização Avançada:** Emprega a propriedade `clip-path` para criar a forma de círculo no plano de fundo, uma técnica moderna que evita o uso de imagens para formas geométricas.
* **Animações:** Aplica `transitions` e a pseudo-classe `:hover` para criar efeitos de animação suaves quando o usuário interage com os botões e o menu, melhorando a experiência de usuário.

**`scripts.js`**

Controla todo o comportamento e a interatividade da página, manipulando os elementos HTML.

* **`trocarCor(cor)`**
    * **Responsabilidade:** Altera a cor de fundo do círculo principal.
    * **Lógica:** Recebe uma string com um código de cor como argumento. Seleciona o elemento com a classe `.circulo` e atualiza sua propriedade `background` com a cor recebida.
* **`trocaImagem(img)`**
    * **Responsabilidade:** Altera a imagem do produto em destaque.
    * **Lógica:** Recebe uma string com o caminho para uma nova imagem. Seleciona o elemento `<img>` com a classe `.copao-starbucks` e atualiza seu atributo `src` para exibir a nova imagem.

### 🚀 Como Executar

Para rodar este projeto, você precisa apenas de um navegador web.

1.  Clone o repositório ou baixe os arquivos (`index.html`, `styles.css`, `scripts.js`) e a pasta `img`.
2.  Abra seu explorador de arquivos.
3.  Navegue até o diretório onde os arquivos estão localizados.
4.  Dê um duplo-clique no arquivo **`index.html`**.

O projeto será aberto no seu navegador padrão e você já poderá interagir com a página.
