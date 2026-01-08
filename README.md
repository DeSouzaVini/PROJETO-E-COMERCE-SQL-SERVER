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
  📥 *Script principal do banco de dados*  
  Contém:
  - Criação das tabelas
  - Chaves primárias e estrangeiras
  - Constraints (`NOT NULL`, `UNIQUE`, `CHECK`)
  - Relacionamentos entre entidades  

⚠️ **Atenção:** este projeto utiliza **filegroups / partition schemes nomeados**.  
Antes de executar o script, crie os filegroups no SQL Server ou ajuste os nomes conforme seu ambiente.

---

- **[`COMERCIO SQLSEVER.brM`](./COMERCIO%20SQLSEVER.brM)**  
  📥 *Arquivo de modelagem do banco*  
  Utilizado para:
  - Definição do modelo lógico
  - Visualização das entidades e relacionamentos
  - Apoio ao desenvolvimento do schema SQL  
  *(Compatível com ferramentas como brModelo)*

---

- **[`modelagem_banco.png`](./modelagem_banco.png)**  
  📥 *Diagrama Entidade-Relacionamento (ER)*  
  Representa:
  - Entidades
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

O modelo segue boas práticas de normalização e integridade relacional.

---

## 🔐 Integridade e Regras de Negócio

O projeto utiliza:
- `PRIMARY KEY` para identificação única
- `FOREIGN KEY` para relacionamento entre tabelas
- `UNIQUE` para evitar duplicidades
- `CHECK` para validação de domínio
- `DEFAULT` para valores automáticos
