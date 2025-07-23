# 🎬 Netflix Dashboard com AWS QuickSight

Projeto realizado como parte da trilha de aprendizado da plataforma [Nextwork](https://learn.nextwork.org/), com foco em visualização de dados usando AWS.

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

## Preview do Dashboard

![Dashboard Netflix QuickSight](./Imagens/netflix_quicksight_dashboard.png)

---

## Etapas do projeto:

1. Preparação dos dados: Dados públicos sobre títulos da Netflix foram tratados e armazenados no Amazon S3.

2. Conexão com o QuickSight: O QuickSight foi configurado para acessar os dados diretamente do S3 por meio de uma fonte de dados do tipo manifest file.

3. Modelagem e análise: Foi realizada a modelagem básica no QuickSight, incluindo criação de campos calculados, filtros e agrupamentos.

4. Criação do dashboard - Montei visualizações para responder perguntas como:

  - Quais os gêneros mais populares?
  - Quantos títulos foram adicionados por ano?
  - Qual o país com mais produções?
  - Distribuição de classificações indicativas (rating)

## Dataset

O dataset utilizado está disponível publicamente no Kaggle. Ele contém dados sobre títulos disponíveis na Netflix, incluindo:

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

Esse projeto me proporcionou uma visão prática e integrada do fluxo de ingestão e visualização de dados na AWS, especialmente utilizando Amazon S3 como fonte e QuickSight como ferramenta de BI. Além disso, pude aplicar conceitos fundamentais de visualização adquiridos no livro Storytelling com Dados, fortalecendo tanto o lado técnico quanto o analítico:

- Boas práticas de visualização, como uso de gráficos circulares segmentados, barras ordenadas, comparação lado a lado e cores consistentes.

- Clareza e objetividade visual, evitando poluição e destacando as informações mais relevantes para o usuário final.

- Aplicação prática de QuickSight, incluindo conexão com o S3, criação de campos calculados, filtros e painéis interativos.

- Raciocínio analítico, ao estruturar visualizações para responder perguntas específicas sobre os dados.
  

### Técnicas visuais aplicadas:

📊 Gráficos de barras horizontais para facilitar a leitura dos eixos.

🎯 Destaques por cor (ex: azul claro x escuro) para segmentação visual intuitiva entre tipos de conteúdo.

🍩 Gráfico de rosca com valor central, para impacto visual direto (testado de forma proposital como alternativa visual).***

📉 Ordenação decrescente para facilitar comparações e priorizar as informações mais relevantes.


***Incluí o gráfico de rosca com valor central de forma intencional, para observar o impacto visual e entender as limitações práticas desse formato comparado a alternativas como gráficos de barras horizontais — mais alinhados às boas práticas.

Seguindo o livro Storytelling com Dados, a autora Cole Nussbaumer Knaflic deixa claro que tanto o gráfico de rosca quanto o de pizza devem ser evitados, pois:

- É difícil comparar as fatias (o olho humano lê melhor comprimento do que ângulo);

- Torna-se confuso com o aumento do número de categorias;

- É visualmente atraente, mas pouco eficiente para transmitir informação com clareza.

Essa escolha foi parte de um experimento visual consciente, visando desenvolver senso crítico na seleção dos melhores gráficos conforme o objetivo da análise.
