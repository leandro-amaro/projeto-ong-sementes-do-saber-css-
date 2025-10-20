# Projeto  ONG "Sementes do Saber"

Este projeto é a segunda parte de uma atividade acadêmica para o curso de Análise e Desenvolvimento de Sistemas. O objetivo desta etapa (Atividade 2) foi aplicar conceitos avançados de CSS para estilizar completamente o site de 3 páginas da ONG fictícia "Sementes do Saber", que havia sido estruturada em HTML na atividade anterior.

## Status do Projeto

O escopo da **Atividade 2 (Estilização com CSS)** está 100% finalizado.

O projeto continuará a ser desenvolvido nas próximas etapas:
* **Atividade 3:** Inclusão de JavaScript para validação de formulário.
* **Atividade 4:** Junção dos módulos e melhorias gerais no projeto.

## 🗂️ Páginas do Projeto

O site é composto por 3 páginas principais, todas conectadas ao mesmo arquivo `style.css`:

1.  **`index.html`**: A página principal (home) com a apresentação da ONG.
2.  **`projetos.html`**: Uma página detalhando as iniciativas e como ajudar.
3.  **`cadastro.html`**: A página de formulário para cadastro de novos voluntários.

## 🚀 Tecnologias Utilizadas

* **HTML5:** Para a estrutura semântica do conteúdo.
* **CSS3:** Para toda a estilização visual e layout.

## 💡 Principais Conceitos de CSS Aplicados

Esta atividade foi um mergulho nos fundamentos do CSS moderno. Os principais conceitos praticados foram:

* **CSS Reset e Box Sizing:** Uso do seletor universal (`*`) para zerar margens/paddings e aplicar `box-sizing: border-box`, garantindo um controle de layout previsível e consistente entre navegadores.
* **Variáveis CSS (`:root`):** Centralização de toda a paleta de cores, fontes e espaçamentos no `:root` para fácil manutenção e consistência global.
* **Layout com Flexbox (`display: flex`):** O `display: flex` foi a ferramenta principal para criar layouts complexos de forma simples e "padrônica":
    * Criação do cabeçalho com título e menu alinhados (`justify-content: space-between`).
    * Alinhamento do menu de navegação (`gap`).
    * Criação de um layout de conteúdo na `index.html` com imagem de um lado e texto do outro (`flex-container`).
* **Layout Centralizado:** Uso de `max-width` e `margin: auto` no contêiner `<main>` para criar uma área de leitura confortável e centralizada em telas maiores.
* **Design em "Cards":** Estilização de `<section>` e `<fieldset>` com fundo, bordas arredondadas (`border-radius`) e sombras (`box-shadow`) para agrupar o conteúdo de forma limpa e moderna.
* **Estilização Avançada de Formulários:** Transformação de um formulário HTML padrão em um componente visualmente agradável, com estilização completa de `label`, `input`, `fieldset`, `legend` e `button`.
* **Micro-interações (Hover):** Uso da pseudo-classe `:hover` e da propriedade `transition` para dar feedback visual ao usuário em links e botões.
* **Imagens Responsivas:** Aplicação de `max-width: 100%` e `height: auto` para garantir que as imagens se adaptem ao tamanho do seu contêiner.

## 🖥️ Como Visualizar o Projeto

1.  Clone este repositório para sua máquina local.
2.  Abra a pasta do projeto.
3.  Abra qualquer um dos arquivos `.html` (ex: `index.html`) diretamente no seu navegador.

## 👨‍💻 Autor

* **Leandro** - *[Pode adicionar seu sobrenome ou usuário do GitHub aqui]*
