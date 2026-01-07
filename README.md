# 🛒 Projeto E-commerce – SQL Server (T-SQL)

## 📌 Descrição
Este projeto apresenta um **banco de dados relacional para um sistema de E-commerce**, desenvolvido em **SQL Server**, utilizando **T-SQL**, com foco em:

- Modelagem relacional
- Integridade referencial
- Auditoria de dados
- Regras de negócio
- Estrutura corporativa de banco de dados

O projeto foi criado com objetivo **educacional e de portfólio**, simulando um ambiente real de vendas.

---

## 📂 Arquivos do Projeto

Este repositório contém os seguintes arquivos (clique para acessar ou baixar):

- **[`E_COMERCE.sql`](./E_COMERCE.sql)**  
  📥 *Download do script principal do banco de dados*  
  Contém:
  - Criação das tabelas
  - Chaves primárias e estrangeiras
  - Constraints (NOT NULL, UNIQUE, CHECK)
  - Relacionamentos entre entidades

- **[`COMERCIO SQLSEVER.brM`](./COMERCIO%20SQLSEVER.brM)**  
  📥 *Download do arquivo de modelagem*  
  Utilizado para:
  - Definição do modelo lógico
  - Visualização das entidades e relacionamentos
  - Apoio ao desenvolvimento do schema SQL  
  *(Arquivo compatível com ferramentas de modelagem como brModelo)*

- **[`MODELAGEM DO BANCO.png`](./MODELAGEM%20DO%20BANCO.png)**  
  📥 *Visualização do Diagrama Entidade-Relacionamento (ER)*  
  Representa:
  - Entidades
  - Atributos
  - Cardinalidades
  - Chaves primárias e estrangeiras

---

## 🧱 Modelagem de Dados

O banco de dados é composto pelas seguintes entidades principais:

- **CLIENTE**
- **ENDERECO**
- **TELEFONE**
- **CATALOGO**
- **PRODUTO**
- **VENDEDORES**
- **COMERCIAL**
- **AUDITORIA_GERAL**

O modelo segue boas práticas de normalização e integridade relacional.

---

## 🗂️ Diagrama Entidade-Relacionamento

Visualização direta do diagrama ER:

![Modelo ER](./MODELAGEM%20DO%20BANCO.png)

---

## 🔐 Integridade e Regras de Negócio

O projeto utiliza:
- `PRIMARY KEY` para identificação única
- `FOREIGN KEY` para relacionamento entre tabelas
- `UNIQUE` para evitar duplicidades
- `CHECK` para validação de domínio
- `DEFAULT` para valores automáticos de data

---

## 🕵️ Auditoria de Dados

O banco possui uma tabela de auditoria chamada **AUDITORIA_GERAL**, responsável por registrar operações de:

- INSERT
- UPDATE
- DELETE

As auditorias registram:
- Nome da tabela
- ID do registro
- Campo alterado
- Valor antigo
- Valor novo
- Tipo de operação
- Data e hora da modificação

---

## ⚙️ Banco de Dados Utilizado
- **Microsoft SQL Server**
- Linguagem **T-SQL**

---

## 🎯 Objetivo do Projeto
Demonstrar conhecimento prático em:
- Modelagem de dados
- Criação de bancos relacionais
- Regras de negócio em SQL
- Auditoria via triggers
- Estrutura de banco para sistemas de vendas

---

## 👤 Autor
**Vinicius Souza Martins**


