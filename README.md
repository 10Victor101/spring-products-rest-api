# Products API

## Descrição
Este repositório contém uma API RESTful desenvolvida com Java e Spring Boot. O projeto fornece endpoints para operações CRUD (Criação, Leitura, Atualização e Exclusão) de informações de produtos.

## Requisitos

Necessario ter o Java e o Maven instalados na máquina. <br>

* [Java 17](https://www.oracle.com/br/java/technologies/downloads/#java17)
* [Maven 3.9.5](https://maven.apache.org/download.cgi)
* PostgreSQL
## Endpoints

* Criar Produto<br>
POST /products

* Listar Produtos<br>
GET /products

* Buscar Produto por ID<br>
GET /products/{id}

* Atualizar Produto<br>
PUT /products/{id}

* Excluir Produto<br>
DELETE /products/{id}

## Como compilar e executar a aplicação

Após a instalação dos requisitos: siga os passos abaixo:

1. Clone o repositório.
2. Abra o terminal na pasta raiz do projeto.
3. Execute o comando para iniciar a aplicação:

    ```bash
    mvn spring-boot:run
    ```
