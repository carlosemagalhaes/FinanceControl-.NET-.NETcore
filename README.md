# 💰 FinanceControl - Sistema de Controle de Gastos Pessoais

[![.NET Core](https://img.shields.io/badge/.NET%20Core-8.0-blue)](https://dotnet.microsoft.com/)
[![C#](https://img.shields.io/badge/Language-C%23-green)](https://learn.microsoft.com/en-us/dotnet/csharp/)
[![JWT](https://img.shields.io/badge/Security-JWT-orange)](https://jwt.io/)

O **FinanceControl** é uma API robusta desenvolvida para auxiliar no gerenciamento financeiro pessoal. O projeto foca em organizar receitas e despesas, oferecendo uma interface segura e performática para o controle do saldo mensal.

---

## 🚀 Tecnologias Utilizadas

Este projeto foi construído utilizando as melhores práticas de mercado e o ecossistema moderno da Microsoft:

- **Linguagem:** C#
- **Framework:** .NET Core (Web API)
- **Persistência de Dados:** Entity Framework Core
- **Segurança:** Autenticação e Autorização via **JWT (JSON Web Tokens)**
- **Arquitetura:** Camadas (Domain, Infra, WebApi, Helpers) para melhor manutenção e escalabilidade.
- **Banco de Dados:** SQL Server (ou In-Memory para testes)

---

## 🛡️ Diferenciais de Segurança (AppSec)

Como desenvolvedor com foco em cibersegurança, este projeto implementa:
- **Autenticação Stateless:** Proteção de rotas via JWT.
- **Data Protection:** Tratamento de dados sensíveis.
- **Validação de Input:** Proteção básica contra tentativas de injeção de dados via Fluent Validation/Data Annotations.

---

## 📂 Estrutura do Projeto

O projeto está dividido em camadas para respeitar o princípio de responsabilidade única:

- **WebApi:** Ponto de entrada da aplicação, contendo os Controllers e configurações de Injeção de Dependência.
- **Domain:** Entidades de negócio e interfaces principais.
- **Infra:** Implementação do contexto do banco de dados (EF Core) e repositórios.
- **Helpers:** Classes utilitárias e extensões compartilhadas.

---

## 🛠️ Como Executar o Projeto

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/carlosemagalhaes/FinanceControl-.NET-.NETcore.git](https://github.com/carlosemagalhaes/FinanceControl-.NET-.NETcore.git)

    Acesse a pasta da WebApi:
    Bash

    cd FinanceControl-.NET-.NETcore/WebApi

    Restaure as dependências e execute:
    Bash

    dotnet restore
    dotnet run

    Acesse o Swagger (Documentação da API):
    Geralmente em: https://localhost:5001/swagger

👤 Autor

Carlos Eduardo Magalhães

    LinkedIn: linkedin.com/in/carlosemagalhaes

    Área de Atuação: Desenvolvedor .NET | Especialista em Segurança da Informação
