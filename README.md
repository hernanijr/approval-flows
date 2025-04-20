# 🔁 Sistema de Aprovação com Fluxos Dinâmicos

Backend em NestJS para criação e gestão de processos com múltiplas etapas de aprovação, com regras dinâmicas por tipo de processo.

## 🧠 Visão Geral

Esse sistema permite configurar diferentes fluxos de aprovação (como desligamentos, contratos, compras), onde cada tipo tem suas fases, regras e responsáveis definidos por dados em banco, sem necessidade de deploy para mudanças.

## 🛠️ Tecnologias

- NestJS
- TypeORM / Prisma
- PostgreSQL / MySQL
- Docker
- Swagger
- Jest (testes unitários)

## 📦 Funcionalidades

- Criação de tipos de processo com fluxos personalizados
- Transições com regras e logs
- Ações: aprovar, reprovar, devolver
- API documentada com Swagger
- Testes automatizados

## ⚙️ Como rodar

````bash
git clone https://github.com/hernanijr/approval-flows
cd approval-flows
docker-compose up ```
````
