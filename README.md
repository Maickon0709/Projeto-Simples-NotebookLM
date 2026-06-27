# 🧠 Caderno Temático: Estruturas de Dados e Banco de Dados com NotebookLM

> Projeto prático desenvolvido para o desafio **"Treinando uma IA de Aprendizagem: Explore o Poder do NotebookLM"** da trilha Bradesco | DIO.

---

## 📌 Contexto e Objetivos

Este caderno temático foi criado no **NotebookLM** com foco em **Estruturas de Dados e Banco de Dados**, dois pilares fundamentais para qualquer desenvolvedor back-end ou engenheiro de dados em formação.

O objetivo é consolidar o conhecimento teórico e prático sobre o ecossistema **MySQL** — desde comandos essenciais de SQL até ferramentas de gestão como MySQL Workbench, terminal e phpMyAdmin — e também compreender o funcionamento de **estruturas lineares** como pilhas, filas e deques, além de aprofundar conceitos de **tipagem de variáveis** (inteiros, floats, strings) que impactam diretamente o desempenho e a organização de sistemas.

O material reúne **50 fontes** curadas e organizadas no NotebookLM, formando uma base sólida para estudo, revisão e consulta contínua.

🔗 **Acesse o Caderno no NotebookLM: https://notebooklm.google.com/notebook/0f45ba90-5ff6-4bd5-abfe-9e3c4422611b

---

## 📚 Curadoria de Fontes

As fontes abaixo foram selecionadas por serem abertas, confiáveis e didáticas — ideais para quem está começando na área de dados e programação.

| # | Fonte | Descrição |
|---|-------|-----------|
| 1 | [Google Cloud — MySQL](https://cloud.google.com/mysql?hl=pt-BR) | Documentação oficial do MySQL na nuvem Google, cobrindo conceitos, casos de uso e boas práticas. |
| 2 | [Lenovo Glossary — Data](https://www.lenovo.com/br/pt/glossary/data/?srsltid=AfmBOor8W3C2uQUCMOvjdHsRx14i7UR0Iv54tX92n7x9kbkw4fSIbEXj) | Glossário técnico acessível explicando o conceito de dados e sua importância em ambientes computacionais. |
| 3 | [AWS — O que é SQL?](https://aws.amazon.com/pt/what-is/sql/) | Introdução clara e objetiva ao SQL: o que é, como funciona e por que é a linguagem padrão para banco de dados relacionais. |

---

## 🧪 Engenharia de Prompts e Cicatrizes

Abaixo estão os prompts utilizados no NotebookLM, as respostas obtidas e os aprendizados do processo.

---

### Prompt 1
**❓ Pergunta:**
> "Me explique de forma simples para alguém que nunca interagiu diretamente com dados na programação e vida real o que seria banco de dados e dados na programação."

**✅ Resposta obtida pelo NotebookLM:**

Dados são pedaços individuais de informação — números, palavras, medições ou descrições. Na vida real, seu nome, data de nascimento e peso são exemplos clássicos. Sozinhos não apresentam contexto, mas quando processados se transformam em informação útil.

Na programação, os dados são classificados por tipos: **inteiros (int)** para contar quantidades, **ponto flutuante (float)** para números decimais como preços, **strings (str)** para textos como nomes de usuário, e **booleanos (bool)** para verdadeiro ou falso.

Um banco de dados funciona como um antigo armário de escritório: o armário inteiro é o banco de dados, as pastas dentro são as tabelas, as fichas dentro das pastas são os registros (linhas), e os campos preenchidos em cada ficha são as colunas. Para interagir com esse "armário digital" usamos um SGBD (como o MySQL) e nos comunicamos com ele através do SQL.

**⚠️ Dificuldade encontrada:**
A resposta inicial foi abrangente mas pouco visual. Foi necessário explorar as perguntas sugeridas pelo próprio NotebookLM — como *"O que significa dizer que um banco de dados é relacional?"* — para aprofundar a compreensão além da analogia do armário.

---

### Prompt 2
**❓ Pergunta:**
> "Me explique pra que serve e porque são importantes as estruturas de dados dentro da computação."

**✅ Resposta obtida pelo NotebookLM:**

Uma estrutura de dados é um jeito organizado de guardar informações na memória do computador para que possam ser usadas da forma mais eficiente possível. Elas unem os dados às operações que podemos fazer com eles — inserir, remover ou buscar uma informação.

Existe uma máxima na computação: **"Programas = Algoritmos + Estruturas de Dados"**. Enquanto o algoritmo é o passo a passo (a receita), a estrutura de dados é o ingrediente organizado. Cada estrutura resolve um problema real:

- **Pilhas (Stack):** fundamentais para o botão "desfazer" (Ctrl+Z), onde a última ação feita deve ser a primeira a ser revertida.
- **Filas (Queue):** garantem a ordem em sistemas de impressão ou streaming, processando dados na ordem exata em que chegaram.
- **Árvores (Trees):** permitem encontrar um arquivo entre milhões de outros instantaneamente.
- **Listas Ligadas:** ideais quando não sabemos quantos dados teremos e precisamos inserir ou remover itens com frequência.

A escolha errada de estrutura pode tornar um sistema extremamente lento — buscar um produto em 2 milhões de itens pode levar segundos com busca sequencial, mas milissegundos com a estrutura certa.

**⚠️ Dificuldade encontrada:**
O modelo focou bastante na teoria. Foi preciso explorar as sugestões de follow-up para entender casos de uso concretos. A conexão entre estruturas e algoritmos foi o ponto mais valioso da resposta.

---

### Prompt 3
**❓ Pergunta:**
> "O que seria SQL e MySQL, e pra que servem?"

**✅ Resposta obtida pelo NotebookLM:**

**SQL** (Structured Query Language) é uma linguagem padronizada para interagir com bancos de dados relacionais. É declarativa — você descreve *o que* quer obter, e o sistema decide *como* fazer. Criada na década de 1970 pela IBM, suas instruções se dividem em categorias:

- **DDL:** estrutura do banco (CREATE, DROP)
- **DML:** manipulação de dados (INSERT, UPDATE, DELETE)
- **DQL:** consultas para recuperar dados (SELECT)
- **DCL e TCL:** controle de permissões e transações

**MySQL** é o SGBD (Sistema de Gerenciamento de Banco de Dados) que executa os comandos SQL. Lançado em 1995, pertence hoje à Oracle e é usado por Facebook, Netflix, YouTube e Wikipedia. A relação entre os dois é simples: **SQL é o idioma, MySQL é o programa que fala esse idioma.**

**⚠️ Dificuldade encontrada:**
A confusão inicial entre SQL (linguagem) e MySQL (sistema) é comum para iniciantes. O NotebookLM sugeriu perguntas de acompanhamento como *"O que acontece se eu usar UPDATE sem a cláusula WHERE?"* que ajudaram a aprofundar o entendimento de forma prática e segura.

---

## 📖 Miniguia de Estudo

### 🗂️ Resumos Estruturados

**Banco de Dados**
Sistema organizado para armazenar, gerenciar e recuperar informações. Os bancos relacionais organizam os dados em tabelas com linhas e colunas, conectadas entre si por relacionamentos. A comunicação é feita via SQL através de um SGBD.

**Comandos SQL Essenciais**
- `CREATE TABLE` — cria uma nova tabela
- `ALTER TABLE` — modifica a estrutura de uma tabela existente
- `INSERT INTO` — insere novos registros
- `SELECT` — consulta e recupera dados
- `UPDATE` — atualiza registros existentes
- `DELETE` — remove registros

**Estruturas de Dados Lineares**
- **Pilha (Stack):** LIFO — último a entrar, primeiro a sair. Ex: Ctrl+Z em editores de texto.
- **Fila (Queue):** FIFO — primeiro a entrar, primeiro a sair. Ex: fila de impressão.
- **Deque:** permite inserção e remoção em ambos os lados.

**Tipagem de Variáveis**
- `INT` — números inteiros (ex: quantidade de alunos)
- `FLOAT / DECIMAL` — números decimais (ex: preço, altura)
- `VARCHAR / TEXT` — textos (ex: nome, descrição)
- `BOOL` — verdadeiro ou falso (ex: usuário ativo?)
- `DATE / DATETIME` — datas e horários

---

### 📋 Glossário de Conceitos

| Termo | Definição |
|-------|-----------|
| **Dado** | Peça individual de informação (número, texto, data) sem contexto próprio |
| **Banco de Dados** | Repositório digital organizado para armazenar e gerenciar informações |
| **SGBD** | Software que gerencia e controla o banco de dados (ex: MySQL) |
| **SQL** | Linguagem declarativa padrão para interagir com bancos relacionais |
| **MySQL** | SGBD relacional de código aberto que usa SQL como linguagem |
| **Tabela** | Estrutura que organiza dados em linhas e colunas |
| **Registro (linha)** | Um item individual dentro de uma tabela |
| **Coluna (campo)** | Atributo de um registro (ex: "Nome", "Idade") |
| **Chave Primária** | Identificador único de cada registro em uma tabela |
| **Chave Estrangeira** | Campo que referencia a chave primária de outra tabela |
| **Estrutura de Dados** | Forma organizada de guardar dados na memória para uso eficiente |
| **Algoritmo** | Conjunto de instruções passo a passo para resolver um problema |
| **Pilha (Stack)** | Estrutura LIFO: último a entrar, primeiro a sair |
| **Fila (Queue)** | Estrutura FIFO: primeiro a entrar, primeiro a sair |
| **Deque** | Estrutura com inserção/remoção em ambas as extremidades |
| **DDL** | Linguagem de Definição de Dados — estrutura do banco (CREATE, ALTER, DROP) |
| **DML** | Linguagem de Manipulação de Dados — registros (INSERT, UPDATE, DELETE) |
| **DQL** | Linguagem de Consulta de Dados — recuperação via SELECT |
| **Tipagem** | Definição do tipo de dado que uma variável pode armazenar |
| **Booleano** | Tipo de dado com apenas dois valores: verdadeiro ou falso |

---

### 🔁 Prompts Reutilizáveis para Revisão

```
1. "Explique o conceito de [TERMO] com um exemplo do dia a dia."

2. "Qual a diferença entre [CONCEITO A] e [CONCEITO B]? Use uma analogia simples."

3. "Crie um exemplo prático de como usar o comando [COMANDO SQL] em uma situação real."

4. "O que acontece se eu usar [COMANDO] sem a cláusula [CLÁUSULA]? Quais os riscos?"

5. "Faça um resumo dos pontos mais importantes sobre [TEMA] em até 5 tópicos."

6. "Em que situações devo escolher [ESTRUTURA DE DADOS A] em vez de [ESTRUTURA DE DADOS B]?"

7. "Quais são os erros mais comuns ao trabalhar com [TÓPICO] e como evitá-los?"

8. "Como [CONCEITO] se aplica em sistemas reais como redes sociais ou e-commerce?"
```

---

## 🛠️ Tecnologias e Ferramentas

![NotebookLM](https://img.shields.io/badge/NotebookLM-Google-blue?style=flat-square)
![MySQL](https://img.shields.io/badge/MySQL-Database-orange?style=flat-square)
![SQL](https://img.shields.io/badge/SQL-Language-lightgrey?style=flat-square)

---

*Projeto desenvolvido como parte da trilha **Bradesco | Dados, Cibersegurança e GenAI** na plataforma [DIO](https://web.dio.me).*
