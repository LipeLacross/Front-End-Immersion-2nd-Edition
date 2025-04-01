## 🌐 [English Version of README](README_EN.md)

# Spotify Imersão
# Front-End-Immersion-2nd-Edition

Este é um projeto desenvolvido em React para simular uma interface similar ao Spotify, utilizando componentes reutilizáveis para criar uma experiência de navegação interativa. A aplicação consiste em uma barra lateral de navegação, cabeçalho com controles e busca, uma área principal para playlists e uma seção de artistas.

## 🔨 Funcionalidades do Projeto

- **Sidebar (Navegação Lateral):** Exibe o logo do Spotify, links de navegação para "Início", "Buscar", e a biblioteca do usuário, além de permitir a criação de playlists.
- **Header (Cabeçalho):** Contém botões de navegação (setas), um campo de busca e opções de login e inscrição.
- **Main (Área Principal):** Exibe uma lista de playlists e uma seção para exibição de artistas.
- **Footer (Rodapé):** Oferece a possibilidade de testar o Premium gratuitamente com um botão de inscrição.

### Exemplo Visual do Projeto
![chrome-capture-2025-4-1](https://github.com/user-attachments/assets/f89b91a3-1077-406a-8989-c205f6333ad3)

## ✔️ Técnicas e Tecnologias Utilizadas

- **React:** Biblioteca para a construção da interface.
- **JavaScript (ES6+):** Linguagem para manipulação da lógica da aplicação.
- **HTML5 & CSS3:** Estrutura e estilização da aplicação.
- **FontAwesome:** Biblioteca de ícones usada para melhorar a interface.
- **Create React App:** Ferramenta para inicializar o projeto com configurações básicas.

## 📁 Estrutura do Projeto

- **public/**
  - `favicon.ico`: Ícone do site.
  - `index.html`: Arquivo HTML principal da aplicação.
  - `manifest.json`: Configurações do aplicativo para PWA.
  - `robots.txt`: Instruções para motores de busca.

- **src/**
  - **App.js**: Componente principal que organiza os outros componentes.
  - **App.test.js**: Testes unitários para o componente `App`.
  - **api-artists/**
    - `artists.json`: Dados de artistas utilizados na aplicação.
  - **assets/**
    - **icons/**: Contém ícones como o logo do Spotify e ícones de navegação.
    - **playlist/**: Imagens das playlists para exibição.
  - **componentes/**
    - **Footer/**: Componente que renderiza o rodapé.
      - `Footer.js`: Componente do rodapé com chamada para o Premium.
    - **Header/**: Componente de cabeçalho com busca e botões.
      - `Header.js`: Implementação do cabeçalho com setas de navegação e campo de pesquisa.
    - **Main/**: Componente principal que exibe playlists.
      - `Main.js`: Renderiza as playlists e resultados de artistas.
    - **Sidebar/**: Componente da navegação lateral.
      - `Sidebar.js`: Exibe o menu de navegação e configurações de idioma.
  - `index.js`: Ponto de entrada do React.
  - `reportWebVitals.js`: Monitoramento de performance da aplicação.
  - `setupTests.js`: Configuração para testes com Jest.

## 🛠️ Abrir e rodar o projeto

Para iniciar o projeto localmente, siga os passos abaixo:

1. **Certifique-se de que o Node.js está instalado**:
   - O [Node.js](https://nodejs.org/) é necessário para rodar o projeto. Você pode verificar se já o tem instalado com:
     
   ```bash
   node -v
   ```

- Se não estiver instalado, baixe e instale a versão recomendada.

2. **Clone o Repositório**:
    - Copie a URL do repositório e execute o comando abaixo no terminal:

   ```bash
   git clone <URL_DO_REPOSITORIO>
   cd nome-do-repositorio
   ```

3. **Instale as Dependências**:

   ```bash
   npm install
   ```

4. **Inicie a aplicação**:

   ```bash
   npm start
   ```

   A aplicação será iniciada no navegador, geralmente em `http://localhost:3000`.

## 🌐 Deploy

Para realizar o deploy da aplicação, você pode utilizar serviços como:

- **[Vercel](https://vercel.com/)**
- **[Netlify](https://www.netlify.com/)**
- **[GitHub Pages](https://pages.github.com/)**

Siga as instruções de cada serviço para configurar o deploy e tornar a aplicação acessível na web.
