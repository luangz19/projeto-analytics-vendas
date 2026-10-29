# 📊 SulVarejo Analytics

Projeto de análise de dados desenvolvido para simular um ambiente real de uma empresa varejista.

O objetivo é construir um fluxo completo de análise de dados, desde o armazenamento e consulta dos dados até a análise e visualização de indicadores de negócio.

## 🎯 Objetivos

O projeto busca responder perguntas de negócio relacionadas a:

- vendas;
- produtos;
- clientes;
- categorias de produtos;
- faturamento;
- custos e margens;
- desempenho comercial.

## 🛠️ Tecnologias

- PostgreSQL
- SQL
- Docker
- Python
- Pandas
- Power BI
- Git
- GitHub

## 🗄️ Banco de dados

O banco PostgreSQL é executado em um container Docker.

Atualmente, o modelo possui as tabelas:

- `clientes`
- `produtos`
- `vendas`

As tabelas são relacionadas por chaves primárias e estrangeiras.

## 📁 Estrutura do projeto

projeto-analytics-vendas/

- `data/` — dados utilizados nas análises
- `sql/` — scripts e consultas SQL
- `notebooks/` — análises exploratórias
- `src/` — códigos Python
- `dashboard/` — dashboards e visualizações
- `docker-compose.yml` — configuração do PostgreSQL
- `README.md` — documentação do projeto

## 📚 SQL

Até o momento foram trabalhados:

- `SELECT`
- `WHERE`
- `AND`
- `ORDER BY`
- `LIMIT`
- cálculos entre colunas
- aliases com `AS`
- `COUNT`
- `AVG`
- `MIN`
- `MAX`
- `GROUP BY`
- `HAVING`

Também foram realizadas análises de margem bruta e margem percentual dos produtos.

## 🚧 Status

Em desenvolvimento.

Próximas etapas:

- consultas com `JOIN`;
- análise das vendas;
- integração com Python/Pandas;
- construção de indicadores;
- desenvolvimento do dashboard.
