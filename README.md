# REST API for Gym Management

🇧🇷 Version in Portuguese: [click here](./README-pt_BR.md)

## About the Development

Contributors:

- [Enricco Gemha](https://github.com/G3mha)
- [Antônio Amaral](https://github.com/AntonioAEMartins)

Project developed for the **Big Data** course in the **Computer Engineering** program at **Insper**.

## Objective

The project aims to develop a microservice for managing gym members and plans.

For this purpose, a RESTful API was created to manage the registration of gym members and plans, following the CRUD (Create, Read, Update, Delete) model. The API offers the following functionalities:

- Users can manage member registration, including creating, reading, updating, and deleting member information.
- Users can manage plan registration, including creating, reading, updating, and deleting plan information.

## Tools Used

The API uses Python's FastAPI framework.

To integrate it with a database, SQLAlchemy was used, which is an ORM (Object Relational Mapper) for Python. SQLAlchemy allows users to write Python code to manipulate a database without having to write SQL directly. PostgreSQL was chosen as the database for the project.

## Project Features Demonstration Video

[Link: https://youtu.be/gqzUmahmUUI](https://youtu.be/gqzUmahmUUI)

## Entity-Relationship Diagram

![ER Diagram](diagrama_ER.png)
