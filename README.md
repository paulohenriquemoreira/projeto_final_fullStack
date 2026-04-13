# 🚀 Desafio Final - Empower 5.0  - Em construção

### Este projeto foi desenvolvido a partir do desafio sobre enchentes no Brasil. Ao analisar o cenário, identifiquei a dificuldade relacionada a Falta de Informação sobre Abrigos, o que motivou a criação desta solução.


## 🚀 Tecnologias Utilizadas

<p align="left">
    <img 
        height="65"
        src="https://raw.githubusercontent.com/marwin1991/profile-technology-icons/refs/heads/main/icons/react.png"
        title="React"
    />
    <img 
        height="65"
        src="https://raw.githubusercontent.com/marwin1991/profile-technology-icons/refs/heads/main/icons/sass.png"
        title="Sass"
    />
    <img
        height="65"
        src="https://raw.githubusercontent.com/marwin1991/profile-technology-icons/refs/heads/main/icons/express.png"
        title="Express"
    />
    <img
        height="65"
        src="https://raw.githubusercontent.com/marwin1991/profile-technology-icons/refs/heads/main/icons/node_js.png"
        title="Nodejs"
    />
    <img
        height="65"
        src="https://raw.githubusercontent.com/marwin1991/profile-technology-icons/refs/heads/main/icons/postman.png"
        title="Postman"
    />
    <img
        height="65"
        src="https://raw.githubusercontent.com/marwin1991/profile-technology-icons/refs/heads/main/icons/sqlite.png"
        title="SQLite/SQLite3"
    />
</p>

## ▶️ Como Rodar o Projeto

Siga os passos abaixo para rodar a aplicação localmente:

**1º Clone esse repositório:**

   ```
   git clone https://github.com/paulohenriquemoreira/projeto_final_fullStack

   cd projeto_final_fullStack
   ```

**2º Instale as dependências:**

   ```
   npm install
   npm install sass
   npm install express
   npm install sqlite3
   npm install sqlite
   npm install cors
   ```

**3º Inicie o servidor de desenvolvimento:**

   ```
   npm run dev
   **Servidor rodando na porta http:localhost:3000
   ```

## 🗄️ Banco de Dados

O banco de dados é criado automaticamente ao iniciar o projeto

```
abrigos.db
```

## 📋 Estrutura da Tabela (Paciente)

| Campo            | Descrição                 |
| ---------------- | ------------------------- |
| id               | Identificador único       |
| nome_abrigo      | Nome Abrigo               |
| endereco_abrigo  | Endereço do abrigo        |
| capacidade_total | Número de máximo de vagas |
| vagas_disponiveis| Número de vagas disponiveis |
| aceita_pet       | Verifica se abrigo aceita pet |
| aceita_doacoes   | Verifica se abrigo aceita doações|


## 🔗 Endpoints

### 📍 Rota inicial

```
GET /
```

Retorna uma página HTML com informações da API

### 📄 Listar Abrigos

```
GET /abrigos
```

### 🔍 Buscar abrigos (id)

```
GET /abrigos/:id
```

Ex: <code>/abrigos/1</code>

### ➕ Criar cadastro de abrigo

```
POST /abrigo
```

### ✏️ Atualizar cadastro de abrigo

```
PUT /abrigo/:id
```

### ❌ Deletar cadastro de abrigo

```
DELETE /abrigo/:id
```

## 🎯 Objetivo do Projeto

Este projeto foi desenvolvido com foco em aprendizado de Full Stack utilizando React, Sass, Node.js + Express,SQLite, Postman e boas práticas no desenvolvimento de APIs.


## 🔐 Segurança

 A API utiliza queries parametrizadas para evitar SQL Injection:

```SQL
WHERE id = ?
```
 ✔️ Boa prática essencial em aplicações backend


## 📚 Conceitos Aplicados

- React
- Sass
- REST API
- CRUD (Create, Read, Update, Delete)
- Arquitetura básica em camadas
- Métodos HTTP (GET, POST, PUT, DELETE)

## 👨‍💻 Autor
 #Projeto desenvolvido para fins educacionais com foco em aprendizado em Formação Full Stack - Paulo Henrique Moreira - 2026.