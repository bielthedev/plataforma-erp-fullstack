# 🚀 Plataforma ERP Fullstack Avançada

Projeto **Fullstack** desenvolvido com foco em **arquitetura, boas práticas e escalabilidade**, simulando um **ERP corporativo** utilizado para gestão financeira, cadastros, autenticação e relatórios.

---

## 🖼️ Arquitetura do Projeto

![Banner](https://github.com/bielthedev/plataforma-erp-fullstack/blob/main/banner.png?raw=true)

---

## 🎯 Objetivo do Projeto

Este projeto foi criado com o objetivo de demonstrar na prática:

- Arquitetura **Fullstack moderna**
- Comunicação via **API REST**
- Separação de responsabilidades (Backend e Frontend)
- Boas práticas com **Spring Boot**
- Frontend desacoplado em **React**
- Integração com **banco de dados SQL**
- Estrutura preparada para evolução e escalabilidade

---

## 🛠️ Tecnologias Utilizadas

### 🔙 Backend
- **Java 17**
- **Spring Boot**
- Spring Web (REST API)
- Spring Data JPA
- Hibernate
- Validações com Bean Validation
- Arquitetura em camadas:
  - Controller
  - Service
  - Repository
  - Model / DTO

### 🎨 Frontend
- **React**
- JavaScript (ES6+)
- Axios (consumo da API)
- Componentização
- Hooks
- Dashboard administrativo

### 🗄️ Banco de Dados
- **SQL**
- Scripts de criação de tabelas
- Relacionamentos entre entidades
- Dados estruturados para relatórios

---

## 📂 Estrutura do Projeto

```bash
plataforma-erp-fullstack/
├── backend/
│   ├── src/main/java
│   │   ├── controller
│   │   ├── service
│   │   ├── repository
│   │   ├── model
│   │   └── dto
│   └── src/main/resources
│       ├── application.properties
│       └── schema.sql
│
├── frontend/
│   ├── src
│   │   ├── components
│   │   ├── pages
│   │   ├── services
│   │   └── App.js
│   └── package.json
│
├── docs/
│   └── arquitetura-erp-fullstack.png
│
└── README.md

