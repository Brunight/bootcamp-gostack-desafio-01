<p align="center">
  <a href="" rel="noopener">
 <img width=200px src="https://rocketseat-cdn.s3-sa-east-1.amazonaws.com/bootcamp-header.png" alt="Project logo"></a>
</p>

<h3 align="center">Desafio 1</h3>

<h4 align="center">Rotas HTTP e Middlewares</h4>

<div align="center">

[![GitHub Pull Requests](https://img.shields.io/github/last-commit/Brunight/bootcamp-gostack-desafio-01)]()
[![Made By](https://img.shields.io/badge/Made%20By-Bruno%20Rodrigues-brightgreen)]()
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div>

<p align="center">
  <a href="#about">Sobre</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#installation">Instalação</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#usage">Uso</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#built_using">Tecnologias Envolvidas</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#authors">Autor</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
</p>


## Sobre <a name = "about"></a>
Resolução desenvolvida para o desafio 1 durante o Bootcamp GoStack 10.0, cujo objetivo era simular um CRUD através de uma Array em Node.Js e Express, e aplicar middlewares para validação das rotas HTTP.

## Instalação <a name = "installation"></a>

```
git clone https://github.com/Brunight/bootcamp-gostack-desafio-01.git
yarn install
yarn dev
```

## Uso <a name="usage"></a>

- `POST /projects`: A rota deve receber `id` e `title` dentro do corpo e cadastrar um novo projeto dentro de um array no seguinte formato: `{ id: "1", title: 'Novo projeto', tasks: [] }`; Certifique-se de enviar tanto o ID quanto o título do projeto no formato string com aspas duplas.

- `GET /projects`: Rota que lista todos projetos e suas tarefas;

- `PUT /projects/:id`: A rota deve alterar apenas o título do projeto com o `id` presente nos parâmetros da rota;

- `DELETE /projects/:id`: A rota deve deletar o projeto com o `id` presente nos parâmetros da rota;

- `POST /projects/:id/tasks`: A rota deve receber um campo `title` e armazenar uma nova tarefa no array de tarefas de um projeto específico escolhido através do `id` presente nos parâmetros da rota;

## Tecnologias Envolvidas <a name = "built_using"></a>

- [Express](https://expressjs.com/) - Server Framework
- [NodeJs](https://nodejs.org/en/) - Backend

## Autor <a name = "authors"></a>

- [@Brunight](https://github.com/Brunight)