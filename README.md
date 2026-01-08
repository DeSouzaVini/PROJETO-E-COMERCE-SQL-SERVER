# 🛒 Projeto E-commerce – SQL Server (T-SQL)

## 📌 Descrição
Este projeto consiste na **modelagem e implementação de um banco de dados relacional para um sistema de E-commerce**, desenvolvido em **Microsoft SQL Server**, utilizando **T-SQL**.

O foco principal está em:

- Modelagem relacional
- Integridade referencial
- Auditoria de dados
- Aplicação de regras de negócio
- Organização corporativa de banco de dados

📚 Projeto desenvolvido com finalidade **educacional e de portfólio**, simulando um ambiente real de vendas.

---

## 📂 Arquivos do Projeto

Este repositório contém os seguintes arquivos (clique para visualizar ou baixar):

### 📄 Script SQL
- **[`E_COMERCE.sql`](./E_COMERCE.sql)**  
  📥 *Script principal do banco de dados*  
  Inclui:
  - Criação das tabelas
  - Definição de chaves primárias e estrangeiras
  - Constraints (`NOT NULL`, `UNIQUE`, `CHECK`)
  - Relacionamentos entre entidades
  - Estrutura preparada para auditoria

⚠️ **Atenção:**  
Este projeto utiliza **filegroups e partition schemes nomeados**.  
Antes da execução do script, é necessário:
- Criar os filegroups no SQL Server  
  **ou**
- Ajustar os nomes das partições conforme o ambiente local

---

### 🧩 Arquivo de Modelagem
- **[`COMERCIO SQLSEVER.brM`](./COMERCIO%20SQLSEVER.brM)**  
  📥 *Arquivo de modelagem lógica do banco*  
  Utilizado para:
  - Visualização das entidades
  - Análise dos relacionamentos
  - Apoio ao desenvolvimento do schema SQL  

  *(Compatível com ferramentas como **brModelo**)*

---

### 🖼️ Diagrama ER
- **[`modelagem_banco.png`](./modelagem_banco.png)**  
  📥 *Diagrama Entidade-Relacionamento (ER)*  
  Representa:
  - Entidades do sistema
  - Atributos
  - Cardinalidades
  - Chaves primárias e estrangeiras

---

## 🗂️ Diagrama Entidade-Relacionamento

Visualização direta do modelo ER:

![Modelo ER](./modelagem_banco.png)

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

A modelagem segue boas práticas de:
- Normalização
- Organização relacional
- Separação de responsabilidades entre entidades

---

## 🔐 Integridade e Regras de Negócio

Foram aplicados os seguintes recursos do SQL Server:

- `PRIMARY KEY` — Identificação única dos registros  
- `FOREIGN KEY` — Garantia de integridade referencial  
- `UNIQUE` — Prevenção de dados duplicados  
- `CHECK` — Validação de domínio  
- `DEFAULT` — Automatização de valores padrão (datas, status, etc.)

---

## 🕵️ Auditoria de Dados

O projeto conta com a tabela **AUDITORIA_GERAL**, responsável por registrar operações de:

- INSERT
- UPDATE
- DELETE

Cada registro de auditoria armazena:
- Tabela afetada
- ID do registro
- Campo alterado
- Valor anterior
- Novo valor
- Tipo da operação
- Data e hora da alteração

Essa abordagem simula um **controle corporativo de alterações no banco**.

---

## ⚙️ Tecnologias Utilizadas
- **Microsoft SQL Server**
- **T-SQL**

---

## 🎯 Objetivo do Projeto
Demonstrar conhecimento prático em:

- Modelagem de dados relacionais
- SQL Server e T-SQL
- Regras de negócio em banco de dados
- Auditoria com triggers
- Estruturação de banco em cenário corporativo

---

## 👤 Autor
**Vinicius Souza Martins**  
Projeto desenvolvido para **estudo, prática e portfólio em Banco de Dados SQL Server**.
