# 🎬 Netflix Dashboard com AWS QuickSight

Projeto realizado como parte da trilha de aprendizado da plataforma [Nextwork](https://learn.nextwork.org/), com foco em visualização de dados usando AWS.

## Objetivo

Explorar o processo de construção de um painel de visualização com **Amazon QuickSight**, partindo de dados armazenados no **Amazon S3**.

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

## Preview do Dashboard

![Dashboard Netflix QuickSight](./Imagens/netflix_quicksight_dashboard.png)

---

## Etapas do projeto:

1. Preparação dos dados: Dados públicos sobre títulos da Netflix foram tratados e armazenados no Amazon S3.

2. Conexão com o QuickSight: O QuickSight foi configurado para acessar os dados diretamente do S3 por meio de uma fonte de dados do tipo manifest file.

3. Modelagem e análise: Foi realizada a modelagem básica no QuickSight, incluindo criação de campos calculados, filtros e agrupamentos.

4. Criação do dashboard: Montei visualizações para responder perguntas como:

  - Quais os gêneros mais populares?
  - Quantos títulos foram adicionados por ano?
  - Qual o país com mais produções?
  - Distribuição de classificações indicativas (rating)

## Dataset

O dataset utilizado está disponível publicamente no Kaggle e foi disponibilizado na plataforma Nextwork para fins educacionais.  
Ele contém dados sobre títulos disponíveis na Netflix, incluindo:

- Nome do título
- Tipo (Filme ou Série)
- Data de lançamento
- Categoria
- País de origem
- etc.

---

## Tecnologias utilizadas

- **Amazon S3** – Utilizado para armazenar os dados brutos em formato CSV, garantindo fácil ingestão e escalabilidade.
- **Amazon QuickSight** – Ferramenta de BI utilizada para se conectar diretamente ao S3, realizar análises e criar visualizações dinâmicas.

---

## Aprendizados

Esse projeto me ajudou a entender melhor o fluxo de ingestão e visualização de dados na AWS, especialmente o uso do S3 com QuickSight.
