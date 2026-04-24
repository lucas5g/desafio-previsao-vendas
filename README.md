# Desafio de Previsao de Vendas

Projeto simples de previsao de vendas mensais usando `pandas`, `matplotlib` e `LinearRegression` do `scikit-learn`.

## Objetivo

Usar os dados de vendas de janeiro a dezembro para:

- organizar os dados em um `DataFrame`
- transformar os meses em uma variavel numerica
- treinar um modelo de regressao linear
- prever o valor de vendas de dezembro com treino ate novembro
- visualizar os dados com histograma e scatter plot

## Estrutura

- `main.ipynb`: notebook com todo o desenvolvimento do desafio

## Tecnologias

- Python
- pandas
- matplotlib
- scikit-learn

## Como funciona

1. Os dados de vendas mensais sao definidos no notebook.
2. Os meses recebem uma representacao numerica em `mes_num`.
3. O modelo e treinado com os meses de janeiro a novembro.
4. Dezembro e usado como dado de teste.
5. O notebook gera a previsao e os graficos para analise.

## Resultado esperado

O notebook realiza a previsao de vendas para dezembro a partir da tendencia observada nos meses anteriores e compara esse comportamento com os dados do conjunto.

## Como executar

Instale as dependencias do ambiente e abra o notebook:

```bash
pipenv install
pipenv run jupyter notebook
```

Depois, abra o arquivo `main.ipynb` e execute as celulas em ordem.

## Observacao

Este projeto tem foco didatico e utiliza um conjunto de dados pequeno, adequado para estudo introdutorio de regressao linear.
