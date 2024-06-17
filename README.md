#Introduction

This project is a simple voting application designed to demonstrate the use of containerized microservices. Each component of the application is deployed as a separate microservice, making the system scalable and easy to manage.

#Architecture

The application consists of the following microservices:

*Voting Service: Allows users to cast their votes.
*Result Service: Displays the results of the voting.
*Worker Service: Processes the votes and stores them in the database.

#Technologies Used

*Docker: Containerization of microservices
*Kubernetes: Orchestration of containerized services
*Redis: In-memory data store used for caching and message brokering
*PostgreSQL: Relational database used for persistent data storage
*Python/Flask: Backend application framework

#Getting Started

Prerequisites
*Docker
*Kubernetes (Minikube or a Kubernetes cluster)
*kubectl
*Redis
*PostgreSQL

