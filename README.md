<h1 align="center">
    <img alt="Be the Hero" src=".github/logo.svg" height="100px" />
    <br>Semana Omnistack #11<br/>
    Node.js | ReactJS | React Native
</h1>


<p align="center">
  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/mathmach/be-the-hero?style=flat-square">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/mathmach/be-the-hero?style=flat-square">
  <img alt="GitHub" src="https://img.shields.io/github/license/mathmach/be-the-hero?style=flat-square"> 
  <img alt="Made by Matheus Machado" src="https://img.shields.io/badge/made%20by-Matheus_Machado-%237519C1?style=flat-square"><br/>
</p>
<p align="center">
  <a href="#bookmark-sobre">Sobre</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#rocket-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#boom-como-executar">Como Executar</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-licença">Licença</a>
</p>

<p align="center">
  <img alt="design do projeto" width="650px" src="./.github/design.png" />
<p>

## :bookmark: Sobre

O **Be the Hero** é uma aplicação Web e Mobile feita para pessoas darem suporte às ONG's cadastradas através de doações. Logo, esta aplicação oferece aos usuários a possibilidade de contatar as ONG's e doar os valores que possam ajudar a causa.
  
Essa aplicação foi realizada durante a **Semana Omnistack #11**, projeto da [Rocketseat](https://rocketseat.com.br/).

## :rocket: Tecnologias

-  [Typescript](https://www.typescriptlang.org/)
-  [Node.js](https://nodejs.org/en/)
-  [ReactJS](https://reactjs.org/)
-  [React Native](http://facebook.github.io/react-native/)
-  [Expo](https://expo.io/)
-  [Express](https://expressjs.com/)
-  [axios](https://github.com/axios/axios)

## :boom: Como Executar

- ### **Pré-requisitos**

  - É **necessário** possuir o **[Node.js](https://nodejs.org/en/)** instalado no computador
  - É **necessário** possuir o **[Git](https://git-scm.com/)** instalado e configurado no computador
  - Também, é **preciso** ter um gerenciador de pacotes seja o **[NPM](https://www.npmjs.com/)** ou **[Yarn](https://yarnpkg.com/)**.
  - Por fim, é **essencial** ter o **[Expo](https://expo.io/)** instalado de forma global na máquina

1. Faça um clone do repositório:

```sh
  $ git clone https://github.com/mathmach/be-the-hero.git
```

2. Executando a Aplicação:

```sh
  # API
  $ cd server
  # Instalando as dependências do projeto.
  $ yarn # ou npm install
  # Configurando o banco de dados e criando as tabelas.
  $ yarn knex:migrate # ou npm run knex:migrate

  # Inicie a API
  $ yarn start # ou npm start

  # Aplicação web
  $ cd web
  # Instalando as dependências do projeto.
  $ yarn # ou npm install
  # Inicie a aplicação web
  $ yarn start # ou npm start

  # Aplicação mobile
  $ cd mobile
  # Instalando as dependências do projeto.
  $ yarn # ou npm install
  # Inicie a aplicação mobile
  $ yarn start # ou npm start
```


## :memo: Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE.md) para mais detalhes.

---
<sup>Projeto desenvolvido com a tutoria de [Diego Fernandes](https://github.com/diego3g), da [Rocketseat](rocketseat.com.br).</sup>
