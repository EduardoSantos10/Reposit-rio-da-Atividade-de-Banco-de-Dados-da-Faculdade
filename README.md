# 📚 Projeto: Sistema de E-Commerce para Livros - Cactus Book

## Experiência Prática: Modelagem e Implementação de Banco de Dados

**Autor:** Eduardo Santos da Silva
**Instituição:** Universidade Cidade de São Paulo
**Data:** Novembro de 2025

## 📝 Descrição
Este projeto consiste na modelagem e implementação de um **Sistema de Gerenciamento de Banco de Dados (SGBD)** para um e-commerce fictício de livros chamado **Cactus Book**.
O objetivo foi criar, popular e manipular um banco de dados relacional que atenda às necessidades transacionais e de consulta de um sistema de vendas online, englobando as entidades **Clientes**, **Livros**, **Pedidos**, **Itens de Pedido**, **Endereços** e **Estoque**.

## 📂 Estrutura e Entregáveis SQL (Atividade 4)
O repositório contém os seguintes scripts SQL, que foram executados no MySQL Workbench, garantindo a **Modelagem Lógica** (3FN) e a **Implementação Física** do projeto:

* **`01_ddl_create_tables.sql`**: Contém a criação do schema e a definição das 6 tabelas (`CREATE TABLE`), incluindo chaves primárias (PKs), chaves estrangeiras (FKs) e restrições (`NOT NULL`, `UNIQUE`).
* **`02_dml_insert_data.sql`**: Contém os comandos `INSERT INTO` para popular as tabelas com dados iniciais (Clientes, Livros, Estoque, Pedidos, etc.).
* **`03_dml_select_queries.sql`**: Contém as 5 consultas de negócio (`SELECT` com `JOIN`, `GROUP BY`, `WHERE` e `ORDER BY`) para extração de informações.
* **`04_dml_update_delete.sql`**: Contém os comandos de manipulação avançada (`UPDATE` e `DELETE`) para simular a manutenção dos dados no sistema.

* ## ⚙️ Tecnologias
* **SGBD:** MySQL (Utilizado o MySQL Workbench para execução).
* **Linguagem:** SQL (Structured Query Language).
* **Controle de Versão:** Git e GitHub.
