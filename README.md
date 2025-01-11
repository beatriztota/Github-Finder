# GitHub Finder

![GitHub Finder](./../img/electrum-page.PNG)

## Descrição

O GitHub Finder é uma aplicação web desenvolvida em TypeScript e React que permite aos usuários pesquisar perfis do GitHub e visualizar seus repositórios. Utilizando a API do GitHub, a aplicação oferece uma interface intuitiva para explorar informações sobre usuários e seus projetos.

## Funcionalidades

- Pesquisa de usuários do GitHub por nome de usuário.
- Exibição de detalhes do perfil do usuário, incluindo avatar, nome e estatísticas.
- Lista de repositórios públicos do usuário com detalhes como nome, linguagem principal e número de estrelas.
- Navegação responsiva e design amigável.

## Demonstração

Você pode acessar uma demonstração do aplicativo [aqui](https://github-finder-tan-rho.vercel.app/).

## Tecnologias Utilizadas

- *React*: Biblioteca JavaScript para construção de interfaces de usuário.
- *TypeScript*: Superset de JavaScript que adiciona tipagem estática.


## Como Executar o Projeto

### Pré-requisitos

- Node.js e npm instalados.
- Uma chave de API do GitHub (opcional, mas recomendado para evitar limitações de taxa).

### Passos para Execução

1. **Clone o repositório**

   ```bash
   git clone https://github.com/beatriztota/github-finder.git
   cd github-finder

2. **Instale as dependências**

   ```bash
   npm install

3. **Configure as variáveis de ambiente**:
crie um arquivo .env na raiz do projeto e adicione sua chave de API do GitHub:

    ```bash
    REACT_APP_GITHUB_API_KEY=your_github_api_key

4. **Execute a aplicação**

   ```bash
   npm start

5. **Abra seu navegador**

   A aplicação estará disponível em http://localhost:3000.
 
