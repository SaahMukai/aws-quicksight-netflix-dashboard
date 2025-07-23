# 🎬 Netflix Dashboard com AWS QuickSight

Projeto de visualização de dados construído com AWS S3 e QuickSight, com ênfase em boas práticas de BI e storytelling com dados.

## Objetivo

O objetivo do projeto foi explorar um dataset público da Netflix com foco em aplicar boas práticas de visualização e dominar ferramentas AWS. Os dados foram carregados no **Amazon S3**, conectados ao **AWS QuickSight**, e organizados em visualizações que respondem perguntas como tendências de lançamento, país de origem, gêneros e distribuição temporal.

---

## O que foi feito

- 🪣 Upload do dataset `netflix_titles.csv` para um bucket no Amazon S3.
- 🔗 Conexão do dataset ao Amazon QuickSight diretamente via S3.
- 💡 Criação de análises com gráficos de barra, tabela e gráfico de rosca.
- 🗂️ Visualização do catálogo de filmes e séries por:
  - Ano de lançamento
  - Tipo (Filme/Série)
  - Data de adição ao catálogo

---
## Dataset

O dataset utilizado está disponível publicamente no Kaggle. Ele contém dados sobre títulos disponíveis na Netflix, incluindo:

- Nome do título
- Tipo (Filme ou Série)
- Data de lançamento
- Categoria
- País de origem
- etc.
- 
---

## Tecnologias utilizadas

- **Amazon S3** – Utilizado para armazenar os dados brutos em formato CSV, garantindo fácil ingestão e escalabilidade.
- **Amazon QuickSight** – Ferramenta de BI utilizada para se conectar diretamente ao S3, realizar análises e criar visualizações dinâmicas.

---

## Preview do Dashboard

![Dashboard Netflix QuickSight](./Imagens/netflix_quicksight_dashboard.png)

---
## ⭐ Outras partes realizadas no projeto

[Etapas do Projeto](etapas.md)

[Armazenamento e Conexão](armconex.md)

[Aprendizados](aprendizado.md) --> Veja aqui o porque do uso do gráfico de rosca

---
