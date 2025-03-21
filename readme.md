# 📌 Plano de Estudo - Microserviços com Node.js, Go, Python e Java

## 🎯 Objetivo
Desenvolver um CRUD completo usando microserviços para praticar Node.js, Go, Python e Java, seguindo boas práticas de mercado. O sistema final incluirá autenticação, mensageria, monitoramento e deploy automatizado.

---

## 🚀 Estrutura do Projeto
- **Node.js** → Serviço de Autenticação
- **Go** → Serviço de Usuários
- **Python** → Serviço de Tarefas
- **Java** → Serviço de Relatórios
- **API Gateway** → Orquestração das chamadas

---

## 📌 Tecnologias Utilizadas
- **Banco de Dados**: DynamoDB
- **Autenticação**: JWT / OAuth
- **Mensageria**: RabbitMQ / Kafka
- **Documentação**: Swagger / OpenAPI
- **CI/CD**: GitHub Actions, Terraform, Kubernetes
- **Monitoramento**: Prometheus, Grafana, ELK Stack
- **Deploy**: AWS (Lambda, ECS, EKS, Serverless Framework)

---

## 📚 Roadmap de Aprendizado

### 1️⃣ Node.js - Serviço de Autenticação
#### 🟢 Iniciante
- Fundamentos de JavaScript e Node.js (ES6+, async/await, módulos)
- Express.js para criação de APIs REST
- Manipulação de JWT para autenticação
- Conexão com DynamoDB usando AWS SDK
- **Projeto:** Criar uma API de login/logout com JWT

#### 🟡 Intermediário
- Arquitetura limpa (controllers, services, repositories)
- Testes com Jest e Supertest
- Autenticação e autorização com OAuth2
- Configuração de CI/CD com GitHub Actions
- **Projeto:** Melhorar o serviço de autenticação com OAuth2 e CI/CD

#### 🔴 Avançado
- Rate-limiting e segurança (Helmet, CORS)
- Mensageria com RabbitMQ/Kafka
- Monitoramento com Prometheus/Grafana
- Deploy na AWS usando Serverless Framework
- **Projeto:** Criar um sistema robusto de autenticação escalável e seguro

---

### 2️⃣ Go - Serviço de Usuários
#### 🟢 Iniciante
- Fundamentos de Go (goroutines, defer, struct, interface)
- Criando APIs REST com Gin
- Integração com DynamoDB
- **Projeto:** Criar um CRUD de usuários básico

#### 🟡 Intermediário
- Arquitetura hexagonal e clean architecture
- Testes unitários com Go Testing
- Implementação de gRPC para comunicação eficiente entre serviços
- **Projeto:** Transformar o CRUD em um microserviço eficiente

#### 🔴 Avançado
- Monitoramento com OpenTelemetry
- Mensageria com RabbitMQ/Kafka
- CI/CD usando Terraform para deploy automatizado
- **Projeto:** Criar um serviço robusto com métricas, logs estruturados e deploy automatizado

---

### 3️⃣ Python - Serviço de Tarefas
#### 🟢 Iniciante
- Python básico (OOP, Asyncio, Flask/FastAPI)
- Conexão com DynamoDB
- **Projeto:** Criar um CRUD de tarefas simples

#### 🟡 Intermediário
- Testes unitários e integração com Pytest
- Arquitetura de microserviços (repos, services, controllers)
- Implementação de WebSockets para atualizações em tempo real
- **Projeto:** Criar um sistema de tarefas colaborativo

#### 🔴 Avançado
- Processamento assíncrono com Celery e Redis
- Logging estruturado e monitoramento com ELK Stack
- Deploy na AWS com Kubernetes
- **Projeto:** Criar um serviço altamente escalável para gestão de tarefas

---

### 4️⃣ Java - Serviço de Relatórios
#### 🟢 Iniciante
- Java básico (OOP, Spring Boot, REST APIs)
- Conexão com DynamoDB usando Spring Data
- **Projeto:** Criar um gerador de relatórios simples

#### 🟡 Intermediário
- Arquitetura limpa e uso do padrão CQRS
- Integração com Kafka para processamento de eventos
- **Projeto:** Criar um sistema de geração de relatórios assíncrono

#### 🔴 Avançado
- Implementação de GraphQL para queries avançadas
- Monitoramento e tracing com Zipkin
- **Projeto:** Criar um serviço escalável de relatórios com otimização de consultas

---

## 🔥 API Gateway e Integração
- Criar um API Gateway com Nginx ou Kong
- Configurar OpenAPI/Swagger para documentação
- Autenticação centralizada via JWT
- Gerenciamento de requisições e load balancing

📌 **Projeto Final: Microserviços Completo**
- 🔹 Autenticação com JWT/OAuth (Node.js)
- 🔹 CRUD de usuários (Go)
- 🔹 Gestão de tarefas (Python)
- 🔹 Relatórios assíncronos (Java)
- 🔹 Mensageria com RabbitMQ/Kafka
- 🔹 Logging, monitoramento e deploy automatizado

---

## 📍 Próximos Passos
1. Começamos pelo **Node.js (Autenticação)**?
2. Criar um template Docker para orquestrar os serviços?
3. Alguma tecnologia adicional que deseja incluir?

# microservices
