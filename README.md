# 🧩 CRUD Full Stack — Go + React + PostgreSQL

Projeto desenvolvido como desafio técnico de implementação de um sistema CRUD completo utilizando:

- Backend em Go
- Frontend em React
- Banco de dados PostgreSQL


## 📌 Funcionalidades

O sistema permite o gerenciamento de:

- Categorias
- Fornecedores
- Produtos


Funcionalidades disponíveis:

✅ Cadastro de registros  
✅ Listagem em tabelas  
✅ Edição de dados  
✅ Exclusão de registros  
✅ Busca de produtos  
✅ Paginação de produtos  
✅ Integração frontend/backend via API REST  


---

# 🚀 Tecnologias utilizadas


## Backend

- Go
- Gin Framework
- PostgreSQL
- SQL
- API REST


## Frontend

- React
- Vite
- React Router DOM
- Axios
- CSS


## Banco de dados

- PostgreSQL


---

# 📂 Estrutura do projeto


```
desafio-react2

├── backend

│   ├── controllers

│   ├── config

│   ├── cmd

│   ├── models

│   ├── repositories

│   ├── services

│   ├── routes

│   ├── utils




├── frontend

│   ├── src

│   │   ├── components

│   │   ├── pages

│   │   ├── styles

│   │   └── api


└── database

    └── scripts SQL
```


---

# ⚙️ Como executar o projeto


## 1. Banco de dados


Entre na pasta:

```
database
```


Execute os scripts SQL no PostgreSQL.


Configure o acesso ao banco no backend.


---

# 2. Backend


Entre na pasta:

```bash
cd backend
```


Instale as dependências:

```bash
go mod tidy
```


Execute:

```bash
go run main.go
```


O servidor será iniciado em:

```
http://localhost:8080
```


---

# 3. Frontend


Entre na pasta:

```bash
cd frontend
```


Instale as dependências:

```bash
npm install
```


Execute:

```bash
npm run dev
```


Aplicação disponível em:

```
http://localhost:5173
```


---

# 🔗 Rotas da API


## Categorias

GET

```
/categorias
```


POST

```
/categorias
```


PUT

```
/categorias/:id
```


DELETE

```
/categorias/:id
```



## Fornecedores

GET

```
/fornecedores
```


POST

```
/fornecedores
```


PUT

```
/fornecedores/:id
```


DELETE

```
/fornecedores/:id
```



## Produtos

GET

```
/produtos
```


POST

```
/produtos
```


PUT

```
/produtos/:id
```


DELETE

```
/produtos/:id
```


Busca e paginação:

```
/produtos?page=1&limit=10&q=nome
```


---

# 🖥️ Interface


A aplicação possui:

- Menu de navegação
- Página inicial
- CRUD de categorias
- CRUD de fornecedores
- CRUD de produtos
- Tabelas responsivas
- Formulários de cadastro e edição


---

# 🗄️ Banco de dados


Principais entidades:


## Categoria

Campos:

- id
- nome


## Fornecedor

Campos:

- id
- nome
- email
- telefone


## Produto

Campos:

- id
- nome
- SKU
- preço
- estoque
- categoria_id


---

# 👩‍💻 Desenvolvimento

Projeto criado para demonstração de integração entre:

React + API REST em Go + PostgreSQL.
