## Etapas do projeto:

1. Armazenamento dos Dados: Dados públicos sobre títulos da Netflix foram baixados do Kaggle em formato .csv e armazenados diretamente no Amazon S3, sem necessidade de tratamento ou preparação prévia.
2. Conexão com o QuickSight: O Amazon QuickSight foi configurado para acessar os dados diretamente do Amazon S3 por meio de um manifest file, permitindo a criação de uma fonte de dados personalizada.
3. Modelagem e análise: Realizei a modelagem básica dentro do QuickSight, com criação de filtros e agrupamentos, preparando os dados para análises exploratórias.
4. Criação do dashboard - Desenvolvi visualizações interativas com o objetivo de responder perguntas como:

  - Quais os gêneros mais populares?
  - Quantos títulos foram adicionados por ano?
  - Qual o país com mais produções?
  - Distribuição de classificações indicativas (rating)
