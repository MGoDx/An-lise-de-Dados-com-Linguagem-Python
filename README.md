# Análise de Dados com Linguagem Python

## Objetivo

Neste projeto o objetivo é colocar em prática o uso da Linguagem SQL dentro do Jupyter Notebook, criando assim um ambiente de análise poderoso com Banco de Dados Relacional, Python e SQL

## Descrição do problema

Temos em mãos um arquivo com dados de pacientes que desenvolveram ou não diabetes. Precisamos gerar uma amostra de dados com os pacientes com mais de 50 anos e para cada um deles indicar em uma nova coluna se o paciente está normal (índice de massa corpórea menor que 30) ou obeso (índice de massa corpórea maior ou igual a 30). Então devemos gerar um novo arquivo CSV e encaminhar para o Cientista de Dados.

## Resolução do problema

Vamos resolver esse problema com Banco de Dados, Python e SQL. Os dados serão inicialmente carregados com Linguagem Python. Faremos então uma cópia dos dados para um banco de dados e usaremos Linguagem SQL para as transformações necessárias. Por fim, copiaremos os dados transformados de volta para um dataframe do Pandas para salvar o resultado em formato CSV.

## Dataset

Usaremos como fonte de dados o dataset PIMA disponível para download no link abaixo:

https://www.kaggle.com/uciml/pima-indians-diabetes-database
