# Análise de Filmes

Projeto de análise de dados de filmes, incluindo tradução de títulos, cálculo de notas médias e visualizações interativas.

## Descrição

Este projeto realiza uma análise completa de um conjunto de dados de filmes, utilizando técnicas de limpeza de dados, manipulação e visualização interativa. As visualizações incluem:

- Gráfico de bolhas (Bubble Chart) de nota média vs ano
- Histograma da distribuição das notas médias
- Boxplot por ano
- Top 20 filmes por nota média
- Scatter plot (ou substituído por Tree Map/Violin Plot) comparando notas de críticos e público
- Distribuição de filmes por ano
- Top 20 filmes com maior diferença entre críticas e público
- Visualização 3D de notas críticas x notas do público x ano

O projeto também lida com **arquivos grandes** usando Git LFS, garantindo que datasets extensos sejam versionados corretamente no GitHub.

## Tecnologias e Bibliotecas Utilizadas

- Python 3.11
- Pandas
- Plotly Express
- Googletrans (para tradução de títulos)
- Git & Git LFS

## Estrutura do Projeto

Projeto Filmes/
│
├─ movies.csv # Dataset original de filmes
├─ movies_traduzido.csv # Dataset com títulos traduzidos
├─ movie.ipynb # Notebook principal de análise
├─ graficos.ipynb # Notebook com visualizações
├─ README.md # Este arquivo
└─ .gitattributes # Configuração do Git LFS

## Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/ArthurTheWorld/AnaliseFilmes.git
   cd AnaliseFilmes
