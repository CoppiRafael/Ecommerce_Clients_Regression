# Projeto de Regressão Linear: Análise de Clientes de Ecommerce

## Visão Geral

Este projeto realiza uma análise de dados de clientes de um site de comércio eletrônico usando um conjunto de dados disponível no Kaggle. O objetivo é construir um modelo de regressão linear para prever o valor gasto anual por clientes com base em diferentes características. A análise se concentra em entender quais variáveis têm maior impacto nos gastos anuais e fornecer recomendações para a empresa sobre onde direcionar seus esforços para maximizar os ganhos.

### Conjunto de Dados

O conjunto de dados inclui as seguintes variáveis:

- **Média Duração da Sessão**: Tempo médio gasto em sessões de aconselhamento de estilo na loja, em minutos.
- **Tempo no Aplicativo**: Tempo médio gasto no aplicativo, em minutos.
- **Tempo no Site**: Tempo médio gasto no site, em minutos.
- **Duração da Associação**: Tempo em anos que o cliente é membro.
- **Valor Anual Gasto**: Valor total gasto pelo cliente em um ano.

## Objetivo

O objetivo deste projeto é ajudar a empresa a decidir se deve investir mais na experiência do aplicativo móvel ou no site para desktop. Utilizamos modelos de regressão linear para analisar a relação entre as variáveis preditoras e o valor gasto anual, oferecendo insights baseados em dados.

## Obtendo os Dados

O conjunto de dados pode ser encontrado no Kaggle. Para acessar, use o link [aqui](URL_DO_DATASET).

### Carregando e Inspecionando os Dados

``
import pandas as pd
``

# Carregar os dados
``
df_data = pd.read_csv('Ecommerce Customers')
``

# Exibir as primeiras linhas do dataset
``
df_data.head()
``

# Estatísticas descritivas
``
df_data.describe()
``

# Informações gerais do dataset
``
df_data.info()
``

# Remover duplicatas
``
df_data.drop_duplicates(inplace=True)
``
