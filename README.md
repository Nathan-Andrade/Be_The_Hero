<div align="center">
    <img src="https://raw.githubusercontent.com/Nathan-Andrade/Be_The_Hero/87c423ca38587da9db3a60f62e5bb33c6563d8f7/frontend/src/assets/logo.svg" width="300px"/>
</div>

<br />

<h2 align="center">
   :rocket: Semana Oministack 11 :rocket:
</h2>

  ![](https://img.shields.io/github/languages/count/Nathan-Andrade/Be_The_Hero?color=%23e82041)  ![](https://img.shields.io/github/languages/top/Nathan-Andrade/Be_The_Hero?color=%23e82041)  ![](https://img.shields.io/github/repo-size/Nathan-Andrade/Be_The_hero?color=%23e82041) ![](https://img.shields.io/github/last-commit/Nathan-Andrade/Be_The_Hero?color=%23e82041)

<p align="center">
  
</p>


## :computer: Projeto

 Be The Hero é um projeto desenvoldido que conecta ONGs e pessoas para ajudar animais indefesos que estão gravemente feridos.

 <p align="center">
  <img src="https://github.com/Nathan-Andrade/Proffy/blob/master/github/gifDaAplica%C3%A7%C3%A3oWithResponsive.gif?raw=true" >
  <img src="https://github.com/Nathan-Andrade/proffy/blob/master/github/gifMobile.gif?raw=true" >
</p>

 ## :airplane: Tecnologias e Bibliotecas

Este projeto foi desenvolvido com as seguintes tecnologias:

<details>
  <summary>Backend</summary>

-   [Node.js](https://nodejs.org/)
-   [Express](https://expressjs.com/)
-   [Javascript](https://www.typescriptlang.org/)
-   [Cors](https://www.npmjs.com/package/cors)
-   [ESLint](https://eslint.org/)
-   [Prettier](https://prettier.io/)
-   [VS Code](https://code.visualstudio.com/)

</details>

<details>
  <summary>Frontend</summary>

-   [React](https://pt-br.reactjs.org/)
-   [Javascript](https://www.typescriptlang.org/)
-   [Styled Components](https://styled-components.com/)
-   [Context API](https://reactjs.org/docs/context.html)
-   [Axios](https://www.npmjs.com/package/axios)
-   [React Icons](https://react-icons.netlify.com/#/)
-   [Prettier](https://prettier.io/)
-   [VS Code](https://code.visualstudio.com/)

</details>

<details>
  <summary>Mobile</summary>

-   [React Native](https://reactnative.dev/)
-   [Expo](https://expo.io/learn)
-   [Styled Components](https://styled-components.com/)
-   [Javascript](https://www.typescriptlang.org/)
-   [React Navigation](https://reactnavigation.org/)
-   [Axios](https://www.npmjs.com/package/axios)
-   [React Native Appearance](https://github.com/expo/react-native-appearance)
-   [Prettier](https://prettier.io/)
-   [VS Code](https://code.visualstudio.com/)

</details>

## :information_source: Como rodar a aplicação

### Requerimentos

Para rodar esta aplicação você vai precisar ter instalado:
* [Git](https://git-scm.com)
* [Node](https://nodejs.org/)
* [Yarn](https://yarnpkg.com/) 

Eu utilizei o banco de dados relacional [SQLite](https://www.npmjs.com/package/sqlite) para rodar os dados.
<br>
Se você quiser utilizar o SQLite3 faça a seguinte instalação na pasta server.

```bash
# Se você estiver utilizando Npm
$ npm install sqlite3

#  Se você estiver utilizando Yarn
$ yarn add sqlite3

```
### Backend

Agora clone este repositório e instale todas as dependências.
```bash
#Para clonar este repositório
$ git clone https://github.com/Nathan-Andrade/Be_The_Hero.git

# Vá para a pasta do servidor
$ cd backend

#Instale todas as dependências
$ npm install

#Para rodar o backend
$ npm start

```


### Frontend

```bash
# Para rodar a aplicação web (frontend) realize os seguintes comandos
$ cd frontend
$ npm install
$ npm start
```

### Mobile

Esta aplicação foi desenvolvida com Expo. É um software open-source que permite rodar React Native e facilita o processo de rodar a aplicação. [Clique aqui](https://expo.io/learn) para iniciar com o Expo.

```bash
# Instale todas as dependências
cd mobile
yarn install
```

Para você conseguir rodar a aplicação, você vai precisar mudar o endereço em :
[api.js](https://github.com/Nathan-Andrade/Be_The_Hero/blob/master/mobile/src/services/api.js)
```javascript
  baseURL: 'http://192.168.0.105:3333',
```
Coloque o ip da sua máquina local para poder ter acesso como no exemplo: 192.168.0.103.

Agora a aplicação irá rodar em qualquer lugar.

```bash
# Para rodar o aplicativo
yarn start
```

O Expo irá abrir em uma página do seu navegador e com o seu celular poderá escanear o QR Code que irá gerar

> Esta aplicação foi testada em um Samsung Galaxy Grand Duos Prime  e um Moto G2.

---

Desenvolvido com ❤️ por <a href="https://www.linkedin.com/in/nathan-a-1b9436124/">Nathan de Andrade</a>.
