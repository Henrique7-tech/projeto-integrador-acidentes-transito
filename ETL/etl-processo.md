## Processo de ETL (Extração, Transformação e Carga)

### Extração
- Download do dataset no Kaggle.
- Importação dos dados para o ambiente Python utilizando a biblioteca pandas.

### Transformação (Python / pandas)
- Filtragem do período para 2015 a 2022.
- Remoção de colunas vazias (ex: latitude, longitude, regional, delegacia, uop).
- Tratamento de valores nulos.
- Padronização de tipos de dados (datas, números e categorias).
- Criação de colunas derivadas (ano, mês, dia da semana, período do dia).
- Seleção das colunas relevantes para análise.

### Carga
- Geração de um novo dataset tratado (.csv).
- Utilização dos dados tratados para análise exploratória e construção das visualizações.
