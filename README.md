<h1 align="center">Automação de Login</h1>

<p align="center">Projeto para automatizar testes no website Swag Labs</p>

<p align="center">
  <a href="#objetivo">Objetivo</a> •
  <a href="#tecnologias">Tecnologias</a> • 
  <a href="#contribuicao">Contribuição</a> • 
  <a href="#licenc-a">Licença</a> • 
  <a href="#autor">Autor</a>
</p>

<h4 align="center"> 
	🚧  Em construção...  🚧
</h4>

## Objetivo

O objetivo deste projeto é criar uma automação de testes para a página de login do site Swag Labs, com o intuito de verificar o funcionamento das funcionalidades de login, adição de produtos ao carrinho e finalização de compra.

## Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

- [Node.js](https://nodejs.org/en/)
- [TypeScript](https://www.typescriptlang.org/)
- [Playwright](https://playwright.dev/docs/intro)

## Funcionalidades

- [x] Login com usuário e senha corretos
- [x] Falha no login com usuário e senha incorretos
- [x] Acesso negado para usuário bloqueado
- [x] Adicionar um produto ao carrinho
- [x] Preencher formulário para finalizar compra
- [x] Finalizar compra com sucesso

## Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com), [Node.js](https://nodejs.org/en/) e um editor de texto de sua preferência.

### 🎲 Rodando a automação

```bash
# Clone este repositório
$ git clone https://github.com/alyfer-ambrozini/automacao_login-labs.git

# Acesse a pasta do projeto no terminal/cmd
$ cd automacao_login-labs

# Instale as dependências
$ npm install

# Execute a aplicação
$ npx playwright test 
$ npx playwright test --debug (para visualizar o processo da automação)


### 📝 Licença

Este projeto está sob a licença MIT.

### 🦸 Autor

Desenvolvido por Alyfer Ambrozini 👋 Entre em contato!

 [![Linkedin Badge](https://img.shields.io/badge/-Alyfer-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/alyfer-ambrozini-1526a3159/)](https://www.linkedin.com/in/alyfer-ambrozini/) 

