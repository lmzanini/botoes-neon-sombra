# Botões com Efeito de Sombra e Neon usando HTML e SASS

[![Node.js](https://img.shields.io/badge/Node.js-16.x-339933.svg)](https://nodejs.org/)  
[![Sass](https://img.shields.io/badge/Sass-1.50.0-CC6699.svg)](https://sass-lang.com/)  
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=&logo=html5&logoColor=white)

<img src="https://i.imgur.com/1FVg7kr.gif" alt="Exemplo de Botões">

Este projeto apresenta **botões estilizados com efeitos de sombra e neon**, utilizando **HTML5** e **Sass** para criação de estilos modernos e atraentes.  
Os botões possuem transições suaves e efeitos de destaque ao passar o mouse.

## Requisitos

Antes de rodar o projeto, você precisa garantir que as seguintes ferramentas estejam instaladas:

- **Node.js**: Para gerenciar pacotes e executar comandos do Sass. Baixe a versão mais recente [aqui](https://nodejs.org/).
- **Sass**: Uma linguagem de folhas de estilo que facilita a escrita de CSS. É necessário instalá-lo globalmente para compilar os estilos do projeto.

## Instalando o Node.js

1. Acesse o site oficial do [Node.js](https://nodejs.org/).
2. Baixe e instale a versão recomendada (LTS) para o seu sistema operacional.
3. Após a instalação, abra o terminal e verifique se o Node.js foi instalado corretamente com o comando:

   ```bash
   node -v
   ```

## Instalando o SASS

1. Abra o terminal e digite o comando para instalar o Sass globalmente:
   ```bash
   npm install -g sass
   ```
2. Após a instalação, ainda no terminal, verifique se o Sass foi instalado corretamente:
   ```bash
   sass --version
   ```

## Iniciando o Projeto

1. Abra o terminal e navegue até a pasta do seu projeto.
2. Execute o comando abaixo para começar a compilar o arquivo Sass automaticamente:
   ```bash
   sass --watch styles.sass:styles.css
   ```
   - O comando **`sass --watch`** faz com que o Sass "observe" o arquivo `styles.sass` e gere automaticamente o arquivo `styles.css` sempre que houver alterações.
   - **`styles.sass:styles.css`**: Define o arquivo de entrada (`styles.sass`) e o arquivo de saída (`styles.css`).

3. Agora, abra o arquivo `index.html` no navegador para visualizar os botões com os efeitos aplicados.  
   Sempre que você modificar o arquivo `styles.sass`, o Sass atualizará automaticamente o `styles.css`, refletindo as alterações no navegador ao recarregar a página.

## Estrutura do Projeto

O projeto contém os seguintes arquivos principais:

- **`index.html`**: O arquivo HTML principal com a estrutura da página.
- **`styles.sass`**: O arquivo Sass que contém os estilos para os botões.
- **`styles.css`**: O arquivo CSS gerado a partir do `styles.sass`.

---

