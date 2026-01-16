# 🚀 Plataforma ERP Fullstack

![Banner do Projeto](./docs/banner.png)

## 📌 Sobre o Projeto
A **Plataforma ERP Fullstack** é um projeto desenvolvido para simular um **sistema real de gestão empresarial**, aplicando boas práticas de arquitetura, separação de responsabilidades e integração entre backend, frontend e banco de dados.

O objetivo é demonstrar conhecimento técnico em **desenvolvimento Fullstack**, com foco em ambientes corporativos.

---

## 🧠 Arquitetura do Sistema

![Arquitetura do Projeto](./docs/arquitetura.png)

O sistema segue o padrão de **arquitetura em camadas**, amplamente utilizado em aplicações profissionais.

### 🔹 Backend (Spring Boot)
- **Controller** – Responsável por receber as requisições HTTP
- **Service** – Camada de regras de negócio
- **Repository** – Acesso aos dados
- **Model** – Representação das entidades

### 🔹 API REST
- Comunicação desacoplada entre backend e frontend
- Preparada para futuras integrações (mobile, BI, etc.)

### 🔹 Frontend (React)
- Componentização
- Camada de serviços para consumo da API
- Estrutura organizada e escalável

---

## 🖥️ Exemplo de Código

![Código Spring Boot](./docs/codigo-backend.png)

Exemplo de Controller REST utilizando Spring Boot para exposição de endpoints.

---

## 🛠 Tecnologias Utilizadas

### Backend
- Java  
- Spring Boot  
- API REST  

### Frontend
- React  
- JavaScript  
- Axios  

### Banco de Dados
- SQL  

### Outros
- Git  
- GitHub  
- Arquitetura em camadas  

---

## 📂 Estrutura do Projeto
plataforma-erp-fullstack
├── backend-springboot
│ ├── controller
│ ├── service
│ ├── repository
│ ├── model
│ └── resources
│
├── frontend-react
│ ├── components
│ ├── pages
│ └── services
│
├── database
│ ├── schema.sql
│ └── data.sql
│
└── docs
├── banner.png
├── arquitetura.png
└── codigo-backend.png
