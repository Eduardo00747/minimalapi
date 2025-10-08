

# 🚗 Minimal API - Veículos

Bem-vindo à **API de Veículos**, uma aplicação desenvolvida em **.NET 8** utilizando o modelo de **Minimal API**.  
Este projeto tem como objetivo demonstrar a criação de uma API simples, organizada e eficiente, seguindo boas práticas de desenvolvimento.

---

## 🧩 Funcionalidades

- Cadastro de veículos (POST)
- Consulta de veículos (GET)
- Atualização de dados (PUT)
- Exclusão de veículos (DELETE)
- Documentação automática com **Swagger / OpenAPI**
- Endpoint raiz (`/`) com mensagem de boas-vindas e link para o Swagger
- Persistência de dados com **MySQL**
- Estrutura de camadas: `Dominio`, `Infraestrutura`, `DTOs` e `ModelViews`

---

## 🛠️ Tecnologias Utilizadas

- **.NET 8**
- **C#**
- **Entity Framework Core**
- **Swagger / OpenAPI**
- **SQLite** (ou outra base que você estiver usando)
- **Visual Studio Code** / **Visual Studio**

---

## 🧠 Conceitos Estudados

- Minimal APIs no .NET 8  
- Injeção de dependência e serviços  
- Configuração de banco de dados com Entity Framework Core  
- Seed Data (criação automática de usuário administrador)  
- Documentação automática com Swagger UI  

---

## 🚀 Como Executar Localmente

### 1️⃣ Clonar o repositório

git clone https://github.com/<seu-usuario>/minimalapi.git
cd minimalapi

## 🧾 Estrutura de Pastas
```bash
minimalapi/
├── Dominio/
│ ├── Entidade/
│ ├── Interfaces/
│ ├── ModelViews/
│ └── Servicos/
├── Infraestrutura/
│ └── Db/
├── DTOs/
├── Program.cs
└── minimalapi.csproj

```

## 2️⃣ Configurar o banco de dados MySQL

### Atualize o appsettings.json com sua string de conexão:

```bash
{
  "ConnectionStrings": {
    "mysql": "server=localhost;database=minimalapidb;user=root;password=sua_senha"
  }
}

```

## 3️⃣ Aplicar migrações

```bash
dotnet ef database update
```

## 4️⃣ Executar a API

```bash
dotnet watch run
```

## 📘 Documentação

Após iniciar o projeto, acesse:
🔗 http://localhost:5037/swagger



# 🚀 Projeto de Estudo: Minimal API com .NET 8

Este projeto foi criado com o objetivo de **aprender e praticar conceitos de APIs minimalistas no .NET 8**, incluindo:
- Criação de endpoints simples
- Conexão com banco de dados MySQL
- Uso do Entity Framework Core
- Configuração e uso do Swagger

## 🧠 O que foi estudado neste projeto

✅ Criação de endpoints usando `MapGet` e `MapPost`  
✅ Injeção de dependência com `builder.Services.AddScoped()`  
✅ Configuração do banco de dados com `DbContext`  
✅ Criação de classes DTO, ModelView e Entidade  
✅ Uso do Swagger para documentar e testar a API  
✅ Execução e testes com Postman e navegador  

Desenvolvido por Eduardo Alcantara (Duda) 💙

---

## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://eduardo00747.github.io/Meu-Site)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/eduardo-alcantara-de-souza)

