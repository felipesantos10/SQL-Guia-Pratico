# Curso Intensivo de SQL

- O que é um banco de Dados?
    - Local de armazenamento de dados de maneira **organizada ou estruturada**.
- Ha muitas maneiras de organizar um banco de dados como também existem muitos tipos de banco. Em especial tem duas categorias: _Sql_ e _NoSql_.
### SQL
    - Abreviação de _Structured Query Language_ (Linguagem de Consulta Estruturada).
- Geralmente o banco de dados SQL são chamados de _Banco de Dados Relacionais_ pois é constituido de _relações_, que são feitas com tabelas.
- Conexões entre tabelas gera um banco de dados.
- O principal elemento sobre os Bancos de Dados SQL são os esquemas(schema) predefinidos. É a maneirar como os dados serão organizados e estruturados.
- exempos:MySQL,SQLite, PostgreSQL, Oracle e SQL Server.

### NoSql
    - Abreviação de Not only SQL(não so sql)

- Geralmente chamados de _Banco de Dados Não Relacionais_
- Principais caracteristicas:
    - Esquemas Dinamicos( não é preciso ter esquemas pre definidos)
    -  - _**Escalabilidade Horizontal**_: _Capacidade de adicionar mais servidores ou nós ao sistema a medida que a aumento de demanda._
    - Escalavel Horizontamente (os dados podem ser distribuidos em varias maquinas)
    - Exemplos: MongoDB, Cassandra, Redis e Neo4j.

### Sistemas de Gerencimaneto de banco de dados
    - DBMS(Database Management Systems - Sistemas de Gerenciamento de Banco de Dados)
- Caracteristicas Gerais;
    - Importa Dados;
    - Organiza;
    - Gerencia;
- A diferentes tipos de Sistemas que Gerenciam Bancos de Dados, no livro em questão aborda os **RDBMS** ( Relational Database Managemen System - Sistema de Gerenciamento de Banco de Dados Relacional)
- Cada RDBMS te uma implementação de sintaxe diferente do SQL
- Ao procura a sintaxe inclua na pesquina o tipo de RDBM
    - exemplos: Create table datetime _postgresql_
    - exemplos: create table datetime _microsoft sql server_

### Consultas SQL
- 4 principais operações que estão disponiveis no banco de Dados.
    - CRUD (CREATE,READ,UPTADE,DELETE).
    - Cria, ler, atualizar e deletar.

### Instruções SQL
- Instruções SQL são comandos em SQL que realizam uma das operações em CRUD
    - Pode criar e excluir tabelas e atualizar e ler dados.
- Precisa ter acesso de leitura e Gravação em Banco de Dados.
- Pessoas que trabalham com essa atividade geralmente são chamadas de DBA( _database administrator) ou engenheiro de banco de dados.

### Consultas SQL
- _Acesso de leitura_ em um banco de Dados só permite examinar os dados da tabelas.
- Chamados de consultas SQL permite que seja realiza busca e exibição de dados. Também conhecidos como consultas de tabelas
- Cargos: Analista de dados ou Cientist de dados.

### Instrução SELECT
- Consulta mais basica

```sql
SELECT * FROM my_table;
```
obs: Mostre-me todos os dados da tabela my_table - colunas e linhas

-  Palavras MAIUSCULAS são chamadas de _palavras-chaves_(reservadas para operação de algum tipo na operação com os dados)

### Memorize essa ordem

- Todas as consultas SQL conterão algumas dessas clausulas.

```sql
SELECT -- colunas que serão exibidas
FROM -- tabela que será extraidas os dados
WHERE -- Filtra linhas 
GROUP BY -- divide linhas em grupos
HAVING -- filtra linhas agrupadas
ORDER BY -- colunas a serem classificada 
```


