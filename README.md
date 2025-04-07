# DB_biblioteca_comunitaria
# Banco de Dados - Biblioteca Comunitária

Este é um projeto simples de banco de dados relacional criado com o objetivo de praticar modelagem, criação e manipulação de dados usando SQL. Ele simula uma biblioteca comunitária fictícia com funcionalidades básicas como cadastro de livros, empréstimos, devoluções e associação de leitores.

## Objetivos

- Praticar criação de tabelas com chaves primárias e estrangeiras
- Simular relacionamentos (1:N, N:M) em SQL
- Inserir e consultar dados fictícios
- Produzir um banco de dados para fins didáticos e portfólio

## Estrutura do Banco

O banco possui 5 tabelas principais:

1. `leitores` - Cadastro de pessoas que pegam livros emprestados  
2. `livros` - Cadastro dos livros disponíveis  
3. `autores` - Informações sobre os autores  
4. `emprestimos` - Registro de empréstimos de livros  
5. `livros_autores` - Tabela de associação entre livros e autores (relacionamento N:M)

## Scripts incluídos

- Criação do banco de dados
- Criação das tabelas com constraints
- Inserção de dados fictícios
- Consultas simples de exemplo

## Exemplos de consultas

- Livros atualmente emprestados
- Leitores que mais realizaram empréstimos
- Autores com mais livros no acervo
- Lista de livros disponíveis para empréstimo

## Como utilizar

1. Copie o conteúdo do arquivo SQL
2. Execute em um banco de dados PostgreSQL local ou em uma plataforma online como o DB Fiddle ou SQL Fiddle
3. Explore e adapte as consultas conforme desejar

## Autor

Danilo de Avellar Luckner Paslar  
Projeto feito com fins educacionais e demonstrativos.  

