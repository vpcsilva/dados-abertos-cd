# Dados Abertos - Câmara dos Deputados

Um projeto para recuperar e armazenar de forma estruturada os dados abertos da cãmara dos deputados do Brasil.

### Dependências
* psycopg2
* sqlalchemy

### Utilização

#### Dump file
Você pode utilizar o arquivo dump, do banco, que se encontra na pasta dump. Levando em consideração o fato de que o projeto utiliza o banco postgresql.

#### Scripts de importação
1. Primeiro crie o banco de dados de acordo com as informações no arquivo `models.py`
1. execute o script `create.py` para criar as tabelas do schema
1. execute o script `import_from_xml.py` para importar os dados dos arquivos no servidor da câmara


### Exemplos dos dados

#### Total de verba gasta por cada parlamentar

https://plot.ly/~HugoDR/88/#plot

<iframe width="900" height="800" frameborder="0" scrolling="no" src="https://plot.ly/~HugoDR/88.embed"></iframe>





