👤 Cadastro de Usuários — CRUD com Spring Boot

Projeto de API REST desenvolvido em Java com Spring Boot, focado na implementação de um CRUD completo de usuários, utilizando arquitetura em camadas e persistência de dados com JPA.

O objetivo do projeto é praticar conceitos de desenvolvimento back-end, incluindo criação de endpoints REST, separação de responsabilidades, integração com banco de dados e uso do Maven.

📁 Estrutura do Projeto

cadastro-usuario/
│
├── .mvn/
│   └── wrapper/
│
├── src/
│   ├── main/
│   │   ├── java/com/limadev/cadastro_usuario/
│   │   │   ├── business/
│   │   │   │   └── UsuarioService.java
│   │   │   │
│   │   │   ├── controller/
│   │   │   │   └── UsuarioController.java
│   │   │   │
│   │   │   ├── infrastructure/
│   │   │   │   ├── entitys/
│   │   │   │   │   └── Usuario.java
│   │   │   │   │
│   │   │   │   └── repository/
│   │   │   │       └── UsuarioRepository.java
│   │   │   │
│   │   │   └── CadastroUsuarioApplication.java
│   │   │
│   │   └── resources/
│   │       └── application.properties
│   │
│   └── test/
│       └── java/com/limadev/cadastro_usuario/
│           └── CadastroUsuarioApplicationTests.java
│
├── pom.xml
└── README.md

💻 Tecnologias Utilizadas

Java

Spring Boot

Spring Web

Spring Data JPA

Hibernate

Maven

Banco de dados relacional

IntelliJ IDEA


⚙️ Funcionalidades


Cadastro de usuários

Listagem de usuários

Busca por ID

Atualização de dados

Exclusão de usuários

CRUD completo implementado via API REST.

📌 Observações

Projeto desenvolvido apenas como back-end (API REST).

Não possui interface gráfica.

Banco configurável via application.properties.

Estruturado em camadas para facilitar manutenção e escalabilidade.

Desenvolvido com finalidade acadêmica.