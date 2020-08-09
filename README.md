# Proffy (Next Level  Week #2)

## Aplicação

### Proffy é uma aplicação para conectar alunos e professores.

## Configurando o ambiente

### Requisitos
- Ter o [Node.js](https://nodejs.org/en/) instalado em seu computador
- Ter instalado o NPM ou o Yarn
- Instalar globalmente o [Expo](https://expo.io/)

## Como executar o projeto

### Instalação das dependências
#### Após clonar o projeto, executar o comando ```npm install``` ou ```yarn install``` nas pastas:

* server
* web
* mobile

### Banco de dados
#### Dentro da pasta **server**:
* executar o comando ```npm knex:migrate``` ou ```yarn knex:migrate``` para criar o banco de dados

## Visualizando o projeto

* Web: http://localhost:3000
* App: ao executar o projeto na pasta mobile, o Expo abrirá uma janela no navegador, onde é possível escolher como acessar o app (via emulador, abrir o app pela web ou scanear o QR code para abrir diretamente pelo celular).

*O projeto na pasta **server** precisa estar em execução para que o app e o projeto web sejam executados corretamente.*