# Desafio Docker Nginx + NodeJS

<img src=".github/readme/thumbnail.gif" alt="Gif rodando os testes do app">

## :spiral_notepad: Descrição do Desafio

> Nesse desafio você colocará em prática o que aprendemos em relação a utilização do nginx como proxy reverso. A idéia principal é que quando um usuário acesse o nginx, o mesmo fará uma chamada em nossa aplicação node.js. Essa aplicação por sua vez adicionará um registro em nosso banco de dados mysql, cadastrando um nome na tabela people.

O retorno da aplicação node.js para o nginx deverá ser:

```bash
Full Cycle Rocks!

- Lista de nomes cadastrada no banco de dados.
```

Gere o docker-compose de uma forma que basta apenas rodarmos: docker-compose up -d que tudo deverá estar funcionando e disponível na porta: 8080.

## 💻 Pré-requisitos

Antes de começar, verifique se você atendeu aos seguintes requisitos:

- Docker-Compose

## Para rodar a aplicação

```bash
docker-compose up -d
```

## Para acessar a aplicação

```bash
http://localhost:8080/
```