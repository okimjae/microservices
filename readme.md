# 🏗️ Microservices CRUD Project

Este projeto implementa um **sistema de microserviços** completo utilizando **GraphQL**, **mensageria** e **boas práticas de arquitetura**, permitindo aprendizado sólido em várias linguagens e tecnologias modernas.

## 🎯 **Objetivos do Projeto**
✅ Aprender **Node.js, Go, Python e Java** com um sistema realista.<br>
✅ Aplicar **boas práticas** (SOLID, Clean Architecture, CI/CD, Testes).<br>
✅ Utilizar **GraphQL no API Gateway** para otimizar a comunicação entre serviços.<br>
✅ Implementar **mensageria** para comunicação assíncrona (RabbitMQ/Kafka).<br>
✅ Configurar **monitoramento e logs** (Prometheus + Grafana + Loki).<br>
✅ Criar **Feature Flags** para ativar/desativar funcionalidades dinamicamente.<br>
✅ Deploy na **AWS Free Tier** usando **Terraform + Kubernetes**.<br>

## 🏗️ **Arquitetura do Projeto**
O sistema é composto pelos seguintes serviços:

📌 **API Gateway (GraphQL - Node.js)** → Centraliza e orquestra as chamadas entre os serviços.<br>
🔑 **Auth Service (Node.js)** → Gerencia autenticação e autorização via **JWT/OAuth**.<br>
👤 **User Service (Go)** → CRUD de usuários.<br>
📌 **Task Service (Python)** → CRUD de tarefas vinculadas a usuários.<br>
📊 **Report Service (Java)** → Geração de relatórios sobre tarefas concluídas.<br>
📡 **Infraestrutura** → Banco **DynamoDB**, mensageria **RabbitMQ/Kafka**, monitoramento e logging.

## 📂 **Estrutura de Pastas**
```
microservices-crud/
│── api-gateway/            # API Gateway (GraphQL - Node.js)
│── auth-service/           # Serviço de autenticação (Node.js)
│── user-service/           # Serviço de usuários (Go)
│── task-service/           # Serviço de tarefas (Python)
│── report-service/         # Serviço de relatórios (Java)
│── infra/                  # Infraestrutura (Terraform, Kubernetes, Logging, Messaging)
│── docs/                   # Documentação (Swagger/OpenAPI)
│── scripts/                # Scripts úteis
│── docker-compose.yml      # Orquestração dos serviços no ambiente local
│── .github/                # CI/CD pipelines
│── README.md               # Documentação principal
```

## 🛠️ **Tecnologias Utilizadas**
🔹 **Linguagens:** Node.js, Go, Python, Java.<br>
🔹 **Banco de Dados:** DynamoDB.<br>
🔹 **Mensageria:** RabbitMQ ou Kafka.<br>
🔹 **Autenticação:** JWT/OAuth.<br>
🔹 **API Gateway:** GraphQL (Apollo/Nginx).<br>
🔹 **Infraestrutura:** Terraform + Kubernetes (AWS Free Tier).<br>
🔹 **Monitoramento:** Prometheus, Grafana e Loki.<br>
🔹 **CI/CD:** GitHub Actions.<br>

## 🚀 **Próximos Passos**
1️⃣ Criar o monorepo com a estrutura ajustada para múltiplas linguagens.<br>
2️⃣ Configurar Docker Compose para rodar tudo localmente.<br>
3️⃣ Implementar a base dos microserviços.<br>
4️⃣ Adicionar API Gateway (GraphQL - Apollo Server).<br>
5️⃣ Integrar Prometheus + Grafana para monitoramento.<br>
6️⃣ Configurar Feature Flags (Unleash/FF4J).<br>
7️⃣ Criar CI/CD com GitHub Actions.<br>
8️⃣ Deploy na AWS Free Tier usando Terraform + Kubernetes.<br>

🚀 **Objetivo final:** Ter um **sistema completo de microserviços** como portfólio, mostrando domínio em várias linguagens e boas práticas! 🔥
