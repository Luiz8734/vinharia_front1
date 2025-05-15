
# Vinheria Agnello

📖 **Breve descrição do caso**  
A Vinheria Agnello é uma empresa familiar localizada em São Paulo, com mais de 15 anos de atuação no mercado de vinhos, oferecendo uma curadoria especializada com rótulos nacionais e internacionais. Um dos grandes diferenciais da loja sempre foi o atendimento personalizado e consultivo, realizado por profissionais com profundo conhecimento em vinhos.

Durante a pandemia, a vinheria enfrentou dificuldades por depender exclusivamente da loja física. Inicialmente resistente ao e-commerce por considerá-lo impessoal, o proprietário Giulio foi convencido por sua filha Bianca da importância de se adaptar. Assim, decidiu investir no desenvolvimento de um site que pudesse traduzir digitalmente a experiência acolhedora da loja física, mantendo a consultoria e o cuidado com o cliente — pilares da Vinheria Agnello.

Este projeto nasce com o desafio de criar uma presença online que mantenha a essência da marca: calor humano, conhecimento e paixão por vinhos.

---

🗂️ **Estrutura do Projeto**

O site foi dividido em cinco páginas principais, com layout responsivo, imagens ilustrativas e conteúdo cuidadosamente escrito para reforçar a identidade da vinheria:

🔹 **Página Inicial (index.html)**  
Apresenta a vinheria e seu propósito. Um texto de boas-vindas e um destaque visual com imagens envolventes convidam o usuário a explorar mais. Há também um destaque promocional de frete grátis.

🔹 **Conheça Nossa História (pagina2.html)**  
Conta a trajetória da Vinheria Agnello desde suas origens familiares até a consolidação como referência em vinhos artesanais. A página reforça os valores de tradição e cuidado na produção.

🔹 **Catálogo de Vinhos (pagina3.html)**  
Exibe uma vitrine com quatro rótulos, cada um com imagem, descrição e botão para acessar mais detalhes. A apresentação reforça o caráter premium e a curadoria da casa.

🔹 **Preparo do Vinho (pagina4.html)**  
Explica detalhadamente o processo de produção do vinho, da colheita ao engarrafamento. Informativo e educativo, conecta o público com a paixão da vinheria pela qualidade.

🔹 **Página de Contato (pagina5.html)**  
Disponibiliza um formulário para que o usuário envie dúvidas, sugestões ou mensagens. Após o envio, uma animação exibe uma confirmação amigável de sucesso.

---

🎨 **Estilizações CSS Aplicadas**

O projeto utilizou diversas técnicas de estilização em CSS para aprimorar a experiência visual do usuário. Abaixo estão as explicações das regras aplicadas:

- ```css
  nav.nav a:hover {
    border-bottom: 2px solid #fff;
  }
  ```
  Ao passar o mouse sobre os links da navegação, é exibida uma linha branca na parte inferior do texto. Isso fornece um feedback visual ao usuário, indicando qual link está em foco.

- ```css
  .animacao1 {
    animation-duration: 2s;
    animation-name: aparecer;
    animation-iteration-count: infinite;
  }

  @keyframes aparecer {
    0% { opacity: 0 }
    100% { opacity: 1 }
  }
  ```
  Essa regra cria uma animação chamada "aparecer", que altera a opacidade de um elemento de 0 a 1 (de invisível a visível). Com `animation-iteration-count: infinite`, o efeito ocorre continuamente a cada 2 segundos, gerando uma espécie de "piscada" ou fade in/out.

- ```css
  .transformacao1 {
    transform: rotate(30deg);
  }
  ```
  Aplica uma rotação de 30 graus ao elemento, inclinando-o levemente. É útil para destacar elementos com um toque visual criativo.

- ```css
  .transformacao2 {
    transform: scale(2, 1);
  }
  ```
  Essa transformação amplia o elemento horizontalmente em 2x, mantendo a altura original. Pode ser usada para enfatizar botões, imagens ou blocos de conteúdo.

- ```css
  h3::first-letter {
    color: rgb(85, 4, 45);
    text-transform: uppercase;
  }
  ```
  Estiliza a **primeira letra** de todos os títulos `<h3>`, alterando sua cor para vinho escuro e garantindo que fique em letra maiúscula, mesmo que no HTML esteja minúscula. Isso adiciona um detalhe refinado à tipografia dos títulos.

- ```css
  p::first-line {
    color: blueviolet;
  }
  ```
  Modifica apenas a **primeira linha de texto** de todos os parágrafos, dando destaque inicial ao conteúdo com um tom roxo claro (blueviolet).

- ```css
  a.pseudo:visited {
    color: crimson;
  }

  a.pseudo:active {
    color: blue;
  }
  ```
  Define cores diferentes para links com a classe `.pseudo`:  
  - Quando já visitado (estado `:visited`), o link fica vermelho escuro.  
  - Durante o clique (estado `:active`), a cor muda para azul.  
  Esses efeitos ajudam o usuário a distinguir entre links já acessados e ativos.

---

🌐 **Deploy do Projeto na Vercel**

Você pode acessar o site publicado através do link abaixo:

🔗 [Clique aqui para acessar o site](https://coloque-seu-link-da-vercel-aqui.vercel.app)

---

👥 **Integrantes do Grupo**

- **Kevin Carvalho Venancio** — RM: 561459  
- **Nicolas Barnabe da Cruz** — RM: 561997  
- **Luiz Antonio Morais** — RM: 562142

---
