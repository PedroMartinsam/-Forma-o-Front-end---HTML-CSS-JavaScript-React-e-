
# 7_RESPONSIVIDADE - Media Queries em CSS

## Descrição
Projeto de prática de **responsividade** utilizando **HTML e CSS**.  
O objetivo é entender como aplicar **media queries** para alterar estilos de elementos de acordo com o tamanho da tela e orientação do dispositivo.

O projeto demonstra mudanças de cores e visibilidade de elementos com base em **largura mínima e máxima** e **orientação da tela (portrait/landscape)**.

---

## Arquivos do projeto

### 1. `index.html`
Estrutura da página:

- `<meta name="viewport" content="width=device-width, initial-scale=1.0">` para habilitar responsividade  
- Títulos e parágrafos (`<h1>`, `<h3>`, `<p>`)  
- Demonstração de estilos diferentes conforme tamanho da tela e orientação  

### 2. `css/styles.css`
Estilos e media queries:

- `h1` vermelho por padrão, azul em telas com **largura máxima de 500px**  
- `p` com fundo vermelho e texto preto por padrão, mudando para fundo cinza e texto vermelho em telas com **mínimo de 800px**  
- `h3` escondido por padrão e visível apenas em **modo landscape**  

---

## Tecnologias utilizadas
- HTML5  
- CSS3  

---

## Como rodar localmente
1. Clone este repositório ou faça download da pasta do projeto.  
2. Abra `index.html` no navegador.  
3. Redimensione a janela ou altere a orientação do dispositivo para observar as mudanças de estilo.  

---

## Aprendizados
- Uso de **media queries** para criar páginas responsivas  
- Diferença entre `max-width` e `min-width`  
- Alteração de estilo com base na **orientação do dispositivo** (portrait/landscape)  
- Aplicação prática de CSS para design adaptável  

---

> **Sugestão de melhoria visual:**  
> - Aplicar estilos adicionais a outros elementos da página  
> - Testar em diferentes dispositivos e tamanhos de tela  
> - Criar layout completo que se adapte de forma fluida usando Flexbox ou Grid
