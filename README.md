<h1 align="center">
    <img alt="Logo" title="Logo" src="assets/logo.svg">
</h1>

<p align="center"> 
  O “Be The Hero” é um projeto que nos oferece a possibilidade de ser o herói de um animal,
  as ONGS podem se cadastrar pela nossa aplicação web, e registrar casos (descrevendo o caso de um
  animal e estimando o valor que precisa ser atingido para ajuda-lo, ex: um animal que foi atropelado e necessita de R$ 120,00 para sua cirurgia), as pessoas podem ver os casos registrados, e qual foi a ONG que realizou o cadastro do caso, podendo ajudar com uma doação, o app pode ser visto por dispositivos Android e IOS.
</p>

## Aplicação Web

### Landing 

<p align="center">
    <img alt="Landing" title="Landing" src="assets/Web/landingBeTheHero.png">
</p>

### Registro de Ongs

<p align="center">
    <img alt="Registro de Ongs" title="Register Be The Hero" src="assets/Web/RegisterBeTheHero.png">
</p>

### Home 

<p align="center">
    <img alt="Home Page" title="Home" src="assets/Web/homeBeTheHero.png" color="##8257e5">
</p>

### Registro de Casos 

<p align="center">
    <img alt="Registro de casos" title="Case Register" src="assets/Web/CaseRegisterBeTheHero.png" color="##8257e5">
</p>

## Aplicação Mobile

<table>
  <tr>
    <th width="33.3%">
      Loading 
    </th>
    <th width="33.3%">
      Casos
    </th>
    <th width="33.3%">
      Detalhes do Caso
    </th>
  </tr>
  <tr>
    <td>
      <img alt="Loading" title="Loading" width="620" src="assets/Mobile/Loading.jpg">
    </td>
    <td>
        <img alt="Cases" title="Casos" width="620" src="assets/Mobile/Cases.jpg">
    </td>
    <td>
        <img alt="CasesDetails" title="Detalhes do Caso" width="620" src="assets/Mobile/CasesDetails.jpg">
    </td>
  </tr>
</table>

## Funcionalidades

* Criar Usuários;

* Listar Casos;

* Criar Casos.

## Para rodar a aplicação

  ```bash

# Clone este repositório
$ git clone https://github.com/Joaobru/Be-The-Hero.git

# Acesse a pasta do projeto no seu terminal/cmd
$ cd Be-The-Hero-master

# Execute o comando nas pastas server/web/mobile para instalar todas as dependências
$ npm install ou yarn

# Execute a aplicação em modo de desenvolvimento, é importante executar este
# comando primeiro no server depois no web ou mobile
$ npm start ou yarn start

# A aplicação web será aberta na porta:3000 - acesse http://localhost:3000

# Exclusivamente para rodar a aplicação mobile é preciso instalar o Expo 
# no seu celular, quando você rodar a aplicação Mobile com o comando yarn
# start, o seu navegador irá abrir mostrando um QrCode, abra o Expo no seu
# celular, e clique na opção "Scan QR Code", aponte a câmera para o QrCode
# e aproveite para fazer testes no Be the Hero

```


## Tecnologias

  * [Node.js](https://nodejs.org/en/) (Back-End);

  * [ReactJS](https://reactjs.org/) (Web Front-End);

  * [React-Native](https://reactnative.dev/) (Mobile Front-End);

  * [SQLite](https://www.sqlite.org/index.html) (Banco de Dados);




