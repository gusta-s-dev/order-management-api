# Order Management API

API REST desenvolvida com Java e Spring Boot para gerenciamento de usuários, produtos, categorias, pedidos e pagamentos.

O projeto foi criado com o objetivo de aplicar conceitos de desenvolvimento backend utilizando Spring Boot, Spring Data JPA e Hibernate, seguindo uma arquitetura em camadas.

## Tecnologias Utilizadas

- Java 21
- Spring Boot 3
- Spring Web
- Spring Data JPA
- Hibernate
- Maven
- Banco de Dados H2
- REST API

## Funcionalidades

- Cadastro e consulta de usuários
- Gerenciamento de produtos
- Gerenciamento de categorias
- Controle de pedidos
- Associação entre usuários e pedidos
- Associação entre produtos e categorias
- Registro de pagamentos
- Cálculo de subtotais e total dos pedidos

## Arquitetura

O projeto segue uma arquitetura em camadas:

```text
Controller
   ↓
Service
   ↓
Repository
   ↓
Database
