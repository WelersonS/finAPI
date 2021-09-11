<h1 align="center">
    FinAPI
</h1>

<p align="center">
 <a href="#-sobre-o-projeto">Sobre</a> •
 <a href="#-funcionalidades">Funcionalidades</a> •
 <a href="#-como-executar-o-projeto">Como executar</a> • 
 <a href="#-tecnologias">Tecnologias</a> • 
 <a href="#-autor">Autor</a>
</p>


## 💻 Sobre o projeto

 FinAPI - é uma API financeira, em que os usuários podem realizar transações bancárias em suas contas criadas na aplicação.


Projeto desenvolvido durante as aulas do módulo I no bootcamp **Ignite - Trilha Node.JS**  oferecido pela [Rocketseat](https://rocketseat.com.br/).

Conceitos abordados no projeto:
- *Configuração de servidor*
- *Verbos HTTP*
- *Status Code*
- *CRUD*
- *Middlewares*

---

## ⚙️ Funcionalidades

 **Gerencie sua conta bancária:** 
  - [x] Rota para criar uma conta
  - [x] Rota para buscar o extrato bancário do cliente
  - [x] Rota para realizar um depósito
  - [x] Rota para realizar um saque
  - [x] Rota para buscar o extrato bancário do cliente por data
  - [x] Rota para atualizar dados da conta do cliente
  - [x] Rota para obter dados da conta do cliente
  - [x] Rota para deletar uma conta
  - [x] Rota para retornar o saldo da conta

 **Regras de negócio**

- [x] Não deve ser possível cadastrar uma conta com CPF já existente
- [x] Não deve ser possível buscar extrato em uma conta não existente
- [x] Não deve ser possível fazer depósito em uma conta não existente
- [x] Não deve ser possível fazer saque em uma conta não existente
- [x] Não deve ser possível fazer saque quando o saldo for insuficiente
- [x] Não deve ser possível excluir uma conta não existente

---

## 🚀 Como executar o projeto

Este projeto contém:
1. Backend (API) 

### Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
* [Git](https://git-scm.com) 
* [Node.js](https://nodejs.org/en/)
* Yarn
    ```sh
    npm install --global yarn
    ```
Além disto é bom ter um editor para trabalhar com o código como [VSCode](https://code.visualstudio.com/)

#### 🎲 Rodando o Backend (servidor)

```bash

# Clone este repositório em seu diretório via terminal/cmd
$ git clone https://github.com/WelersonS/finAPI.git

# Acesse a pasta do projeto no terminal/cmd
$ cd finAPI

# Instale as dependências
$ yarn

# Execute a aplicação em modo de desenvolvimento
$ yarn start

# O servidor iniciará na porta:3333 - acesse http://localhost:3333 

```


---

## 🛠 Desenvolvido com

* [NodeJS](https://nodejs.org/en/)

* [Express](https://expressjs.com/)


---

## 🦸 Autor

<a href="https://github.com/WelersonS">
 <img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/60586718?s=60&v=4" width="100px;" alt="Welerson"/>
 <br />
 <sub><b>Welerson Robert da Silva 🚀</b></sub></a>
 <br />

[![Linkedin Badge](https://img.shields.io/badge/-Welerson-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/welerson-robert-308308146)](https://www.linkedin.com/in/welerson-robert-308308146/)

---

Feito com ❤️ por Welerson 👋🏽 [Entre em contato!](https://www.linkedin.com/in/welerson-robert-308308146/)

---