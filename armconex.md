## Armazenamento e Conexão do Dataset no Amazon S3 com QuickSight

Para facilitar o acesso e a visualização dos dados no QuickSight, armazenei o dataset netflix_titles.csv em um bucket do Amazon S3 chamado quicksight-project-saahmukai. Também criei e editei um arquivo manifest.json, que é essencial para o QuickSight entender o formato e a localização do dataset.

### O processo foi:

1. Criação do bucket S3 para armazenar os arquivos do dataset.

2. Upload do arquivo CSV (netflix_titles.csv) para o bucket.

3. Modificação do arquivo manifest.json para incluir o caminho correto do CSV no S3.

4. Re-upload do arquivo manifest.json modificado no bucket.

### Na configuração do QuickSight:

1. Criei uma nova fonte de dados do tipo S3, utilizando o bucket criado.

2. Conectei o QuickSight ao arquivo manifest.json para que ele pudesse interpretar corretamente os dados.

3. Importeio o dataset com sucesso, confirmando a conexão.

### Na etapa de análise e visualização:

1. Iniciei a criação dos gráficos e painéis diretamente a partir dos dados importados.

2. Usei campos originais do dataset para montar as visualizações, sem a necessidade de criar campos calculados até o momento.

3. Experimentei tipos diferentes de gráficos, como gráficos de barras e gráficos do tipo donut, para analisar a distribuição de títulos por ano de lançamento, tipos de conteúdo (filmes vs séries) e gêneros.
