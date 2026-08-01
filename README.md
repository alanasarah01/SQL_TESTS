# SQL_TESTS — Exercícios de SQL Intermediário/Avançado

Notebook com a resolução de exercícios de SQL de nível intermediário a avançado, simulando um banco relacional dentro do próprio notebook.

## Stack utilizada
- Linguagem: Python, SQL
- Banco de dados: SQLite (em memória, via sqlite3)
- Ambiente: Google Colab / Jupyter Notebook

## Fonte dos dados
Tabelas fictícias (ex.: funcionários, departamentos, prédios) criadas em memória com pandas para simular cenários de entrevista técnica.

## Arquitetura
pandas (cria DataFrames) -> sqlite3 (carrega como tabelas) -> queries SQL executadas no notebook.

## Principais decisões
- Uso do SQLite via Python em vez de um servidor de banco externo, permitindo rodar tudo dentro do Google Colab sem setup adicional.

## Como rodar o projeto
1. Abra SQL_Tests.ipynb no Google Colab (botão "Open in Colab") ou em um Jupyter local.
2. Execute as células em ordem — cada exercício já contém o enunciado e a query de resposta.

## Resultados
Conjunto de queries resolvidas cobrindo agregações, joins e agrupamentos por múltiplas dimensões.

## Aprendizados
Prática direcionada para perguntas de SQL comuns em processos seletivos de dados (ex.: soma de salário por departamento e prédio).
