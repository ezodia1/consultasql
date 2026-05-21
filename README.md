# Análise SQL: Aplicativo de Leitura

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/postgresql-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-ADADAD?style=for-the-badge)

## 📌 Visão Geral do Projeto
Este projeto analisa o banco de dados de um aplicativo de leitura que ganhou tração durante a pandemia de COVID-19. O banco contém informações sobre livros, autores, editoras, avaliações e resenhas de usuários em 5 tabelas relacionadas. Utilizando SQL como principal ferramenta de análise, foram respondidas 5 perguntas analíticas com o objetivo de gerar insights para o desenvolvimento de um novo produto.

## 🎯 Objetivos de Negócio
* **Catálogo:** Entender a composição do acervo e identificar tendências de publicação.
* **Engajamento:** Analisar o comportamento dos usuários através de avaliações e resenhas.
* **Qualidade:** Identificar autores e editoras de destaque com base em métricas objetivas.

## 🛠️ Stack Técnica
* **Linguagem:** Python
* **Banco de Dados:** PostgreSQL (via SQLAlchemy)
* **Manipulação e Visualização:** Pandas

## 📉 Metodologia
Conexão ao banco de dados remoto via SQLAlchemy e execução de 5 consultas SQL analíticas:

1. **Livros pós-2000:** Contagem de livros publicados após 01/01/2000.
2. **Resenhas e notas por livro:** Média de avaliações e total de resenhas por título.
3. **Editora mais produtiva:** Editora com maior número de livros acima de 50 páginas.
4. **Autor mais bem avaliado:** Autor com maior nota média entre os com pelo menos 50 avaliações.
5. **Engajamento de usuários ativos:** Média de resenhas escritas por usuários que avaliaram mais de 50 livros.

## 🏆 Resultados e Conclusões
* **82% do catálogo** é composto por livros publicados após 2000, indicando um acervo predominantemente atual.
* **Penguin Books** é a editora com maior volume de publicações — 42 livros acima de 50 páginas.
* **J.K. Rowling** lidera em nota média (4.28/5.0) entre autores com pelo menos 50 avaliações.
* Usuários que avaliam mais de 50 livros escrevem em média **~24 resenhas** — indicando que usuários engajados tendem a contribuir mais com conteúdo textual, enriquecendo a experiência da plataforma.

---

### 📂 Estrutura do Repositório
* `projetosql.ipynb`: Notebook Jupyter contendo todas as consultas SQL e análises.

---
**Enzo Bombassaro de Freitas** | *Data Analyst* | [LinkedIn](https://www.linkedin.com/in/enzo-bombassaro/) | [GitHub](https://github.com/ezodia1)
