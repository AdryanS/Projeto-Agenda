# Projeto-agenda 🖋

<br>

<p align="center">
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-como-executar">Como executar</a>&nbsp;&nbsp;&nbsp;
</p>

<br><br>

## ✨ Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- [NodeJS](https://nodejs.org/) 
- [EJS](https://ejs.co/)
- [MongoDB](https://www.mongodb.com/)
- [Express](https://expressjs.com/pt-br/)
- [webpack](https://webpack.js.org/)

<br>

## 💻 Projeto

#### O Projeto Agenda foi desenvolvido para criar agendas de contatos, foi feito no curso do [Luiz Otávio Miranda](https://www.youtube.com/c/Ot%C3%A1vioMiranda), na plataforma de cursos [Udemy](https://www.udemy.com/).

O projeto conta com algumas funcionalidades:

- Uma pagina para criar e entrar em sua conta.
  - Nesse login tem uma segurança de senhas, usando um hash de senhas com [bcryptjs](https://www.npmjs.com/package/bcryptjs).
  - O login também tem um validador de e-mails usando [validator](https://www.npmjs.com/package/validator).
<br>

- Um CRUD de contatos.
  - Create: Cria contatos.
  - Read: Mostra os contatos na tela.
  - Update: Atualiza os contatos.
  - Delete: Deleta os contatos

<br>

## 🚀 Como executar

#### Para executar esse projeto você precisa criar um arquivo no projeto chamado ".env", dentro desse arquivo se deve colocar:

```env
  CONNECTIONSTRING="sua conexão ao MongoDB"
```

```bash 
# para quem utiliza yarn: 

yarn

&

yarn start

# para quem utiliza npm:

npm install

&

npm start

# projeto agenda será executado na porta: http://localhost:3000
```

<br>

### Feito no [Curso de JavaScript e TypeScript do básico ao avançado.](https://www.udemy.com/course/curso-de-javascript-moderno-do-basico-ao-avancado/)
