# Gym-Bros

## Sobre o desenvolvimento

Contribuidores:

- [Enricco Gemha](https://github.com/g3mha)
- [Antônio Amaral](AntonioAEMartins)

*Este é um projeto desenvolvido durante o ministério da disciplina de Megadados no Instituto de Ensino e Pesquisa (Insper).*

## Objetivo

O objetivo do projeto é desenvolver um microsserviço de controle de membros e planos de uma academia. 

Para isso, criou-se uma API RESTful que permita o gerenciamento do cadastro de membros e planos da academia, seguindo o modelo CRUD (Create, Read, Update, Delete). A API oferece as seguintes funcionalidades:

- O usuário pode gerenciar o cadastro de membros, incluindo a criação, leitura, atualização e exclusão de informações de membros.
- O usuário pode gerenciar o cadastro de planos, incluindo a criação, leitura, atualização e exclusão de informações de planos.

## Ferramentas utilizadas

A API utiliza o framework FastAPI do Python.

Para integrá-la a um banco de dados, foi utilizado o SQLAlchemy, que é um ORM (Object Relational Mapper) para Python. O SQLAlchemy permite que o usuário escreva código Python para manipular um banco de dados, sem precisar escrever SQL diretamente. Escolheu-se o PostgresSQL como banco de dados para o projeto.

## Vídeo demonstração das funcionalidades do projeto

[Link: https://youtu.be/gqzUmahmUUI](https://youtu.be/gqzUmahmUUI)

## Diagrama de Entidade-Relacionamento

![Diagrama ER](diagrama_ER.png)
