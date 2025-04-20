# 🎬 Netflix Dashboard com AWS QuickSight

Projeto realizado como parte da trilha de aprendizado da plataforma [Nextwork](https://learn.nextwork.org/), com foco em visualização de dados usando AWS.

## 🧠 Objetivo

Explorar o processo de construção de um painel de visualização com **Amazon QuickSight**, partindo de dados armazenados no **Amazon S3**.

---

## 🔧 O que foi feito

- 🪣 Upload do dataset `netflix_titles.csv` para um bucket no Amazon S3.
- 🔗 Conexão do dataset ao Amazon QuickSight diretamente via S3.
- 💡 Criação de análises com gráficos de barra, tabela e gráfico de rosca.
- 🗂️ Visualização do catálogo de filmes e séries por:
  - Ano de lançamento
  - Tipo (Filme/Série)
  - Data de adição ao catálogo

---

## 📸 Preview do Dashboard

![Dashboard Netflix QuickSight](./imagens/netflix_quicksight_dashboard.png)

---

## 🗃️ Dataset

O dataset usado está disponível publicamente no Kaggle e foi disponibilizado na plataforma Nextwork para fins educacionais.  
Ele contém dados sobre títulos disponíveis na Netflix, incluindo:

- Nome do título
- Tipo (Filme ou Série)
- Data de lançamento
- Categoria
- País de origem
- etc.

---

## 🛠️ Tecnologias utilizadas

- **Amazon S3** – Armazenamento dos dados brutos
- **Amazon QuickSight** – Conexão direta e visualização dos dados

---

## 📚 Aprendizados

Esse projeto me ajudou a entender melhor o fluxo de ingestão e visualização de dados na AWS, especialmente o uso do S3 com QuickSight.
