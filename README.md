# 🔐 Authentication API (JWT)

API RESTful para autenticação de usuários utilizando JWT, com foco em segurança, organização e boas práticas.

## 🚀 Tecnologias

- Node.js
- Express
- JWT (JSON Web Token)
- Argon2
- PostgreSQL / MongoDB

## 🔧 Funcionalidades

- Registro de usuários
- Login com autenticação JWT
- Rotas protegidas
- Hash seguro de senhas
- Middleware de autenticação

## 🔒 Segurança

- Senhas criptografadas com Argon2
- Tokens JWT com expiração
- Proteção de rotas privadas

## 📌 Rotas principais

POST /register  
POST /login  
GET /profile (rota protegida)

## ▶️ Como rodar o projeto

```bash
npm install
npm run dev
