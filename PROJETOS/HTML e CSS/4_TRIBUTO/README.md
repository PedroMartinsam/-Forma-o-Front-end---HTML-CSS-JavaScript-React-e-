# 4_TRIBUTO - The Offspring

## Descrição
Projeto de página de tributo à banda **The Offspring**, criado com **HTML5 e CSS3**.  
A página apresenta biografia, imagens, curiosidades, citações da banda e links externos, com um layout organizado, moderno e responsivo.

O objetivo é praticar estruturação semântica de HTML, estilização com CSS e organização visual de conteúdos.

---

## Arquivos do projeto

### 1. `index.html`
- Estrutura da página:
  - **Cabeçalho**: título e descrição da banda
  - **Imagens**: destaque e segunda imagem com legenda (`<figure>` e `<figcaption>`)
  - **Biografia**: informações sobre a formação da banda e primeiros anos
  - **Citações**: trechos marcantes em `<blockquote>`  
  - **Curiosidades**: lista de fatos interessantes sobre a banda  
  - **Mais informações**: link externo para Wikipedia

### 2. `css/styles.css`
- Estilização aplicada:
  - Fonte padrão Helvetica
  - Layout centralizado com container de largura máxima e padding
  - Estilo de cabeçalho e títulos (`.main-title`, `.main-paragraph`)
  - Estilo de imagens e legendas (`.featured-image`, `.img-bold`)
  - Separação de seções com `border-top` e `border-bottom` dash
  - Citações com destaque (`.quotes-container blockquote`)
  - Lista de curiosidades estilizada (`.curiosities-container li`)
  - Fundo da página em tom claro e container em branco

---

## Tecnologias utilizadas
- HTML5
- CSS3
- Semântica e boas práticas de estrutura de página

---

## Como rodar localmente
1. Clone este repositório ou faça o download da pasta do projeto.  
2. Abra o arquivo `index.html` no seu navegador.  

---

## Aprendizados
- Estrutura semântica de HTML: `<header>`, `<figure>`, `<figcaption>`, `<blockquote>`, `<ul>`, `<li>`  
- Organização visual com CSS: container centralizado, padding, margens, bordas e cores  
- Estilização de textos: fontes, itálico, bold, tamanho de fonte  
- Criação de páginas de tributo com layout limpo e fácil de ler  
- Inclusão de links externos e boas práticas de acessibilidade (`alt` nas imagens)

---

> **Sugestão de melhoria visual:**  
> Para deixar o projeto ainda mais moderno, pode-se adicionar:  
> - **Hover effects** em links e imagens  
> - **Transições suaves** para textos e elementos visuais  
> - **Responsividade** completa usando media queries para telas menores

