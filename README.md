Projeto de Orders com Migrations no Docker
Este projeto em Go exemplifica a criação e gerenciamento de orders com uma arquitetura que inclui banco de dados MySQL, RabbitMQ para mensageria, 
endpoint para chamada Rest, gRPC server e GraphQL server e migrações de banco de dados automatizadas usando Docker.
# Desafio de Listagem de Orders

## Passos para executar o desafio

1. Clone o repositório.
2. Navegue até o diretório do projeto.
3. Execute `docker-compose up` para subir os serviços.

## Serviços e Portas

- **REST API:** http://localhost:8000/order
- **GRPC Service:** Porta 50051
- **GraphQL API:** http://localhost:8080/
