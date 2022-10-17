# Análise de Dados com Linguagem Python

## Objetivo

Neste projeto o objetivo é colocar em prática o uso da Linguagem SQL dentro do Jupyter Notebook, criando assim um ambiente de análise poderoso com Banco de Dados Relacional, Python e SQL

## Descrição do problema

Temos em mãos um arquivo com dados de pacientes que desenvolveram ou não diabetes. Precisamos gerar uma amostra de dados com os pacientes com mais de 50 anos e para cada um deles indicar em uma nova coluna se o paciente está normal (índice de massa corpórea menor que 30) ou obeso (índice de massa corpórea maior ou igual a 30). Então devemos gerar um novo arquivo CSV com os resultados obtidos.

## Dataset

Usamos como fonte de dados o dataset PIMA disponível para download no link abaixo:

https://www.kaggle.com/uciml/pima-indians-diabetes-database

## Resolução do problema

Resolvemos esse problema com Banco de Dados, Python e SQL. Os dados foram inicialmente carregados com Linguagem Python. Foi feita então uma cópia dos dados para um banco de dados e usada Linguagem SQL para as transformações necessárias. Por fim, copiamos os dados transformados de volta para um dataframe do Pandas para salvar o resultado em formato CSV.
