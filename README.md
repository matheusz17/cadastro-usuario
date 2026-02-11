📋 Cadastro de Usuários — CRUD com Spring Boot

API REST desenvolvida em Java utilizando Spring Boot, responsável por realizar um CRUD completo de usuários (Create, Read, Update e Delete).

O projeto foi estruturado em camadas, separando responsabilidades entre Controller, Service (Business), Repository e Entity, seguindo boas práticas de arquitetura.

🚀 Tecnologias Utilizadas

Java

Spring Boot

Spring Web

Spring Data JPA

Maven

Hibernate

Banco de dados relacional (configurável)

IntelliJ IDEA

📁 Estrutura do Projeto
src/main/java/com/limadev/cadastro_usuario


├── controller
│   └── UsuarioController.java
│
├── business
│   └── UsuarioService.java
│
├── infrastructure
│   ├── entitys
│   │   └── Usuario.java
│   │
│   └── repository
│       └── UsuarioRepository.java
│
└── CadastroUsuarioApplication.java

📌 Arquitetura

Controller

Responsável por receber as requisições HTTP:

GET

POST

PUT

DELETE

E encaminhar para a camada de serviço.

Business (Service)

Contém as regras de negócio da aplicação.

É responsável por:

Processar dados

Validar informações

Orquestrar operações entre Controller e Repository

Infrastructure
Entity

Representa a tabela do banco de dados através da classe Usuario.

Repository

Interface que estende JpaRepository, responsável por realizar operações no banco de dados.

⚙️ Funcionalidades

✔️ Criar usuário
✔️ Listar todos os usuários
✔️ Buscar usuário por ID
✔️ Atualizar usuário
✔️ Remover usuário

🎯 Objetivo do Projeto

Projeto desenvolvido para fins acadêmicos, com foco em:

Aprendizado de Spring Boot

Criação de APIs REST

Implementação de CRUD

Organização em camadas

Integração com banco de dados usando JPA