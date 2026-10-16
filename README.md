# Análise de Dados — Auto MPG

## Sobre o projeto

Este projeto utiliza a base Auto MPG para analisar o consumo de combustível de diferentes veículos. O trabalho foi dividido em duas partes: análise e preparação dos dados, e aplicação de modelos de Inteligência Artificial para estimar o consumo.

A base possui 398 registros de veículos e informações como peso, potência, cilindradas, número de cilindros e ano do modelo.

## O que foi feito

- Análise inicial dos dados e de suas características.
- Tratamento dos valores ausentes na coluna `horsepower`.
- Verificação de registros duplicados e valores extremos.
- Criação de gráficos para entender a relação entre as variáveis.
- Análise das correlações com o consumo de combustível.
- Preparação dos dados para treinamento, validação e teste.
- Treinamento e comparação de dois modelos de previsão.

## Modelos utilizados

**MLP (rede neural)**

Modelo treinado para estimar o consumo dos veículos a partir de suas características. Foram testadas configurações diferentes para avaliar o desempenho das previsões.

**Lógica Fuzzy**

Modelo baseado em regras que relacionam o peso e a potência do veículo ao consumo estimado. A proposta também permite comparar um modelo baseado em regras com uma rede neural.

## Principais observações

A análise mostrou uma relação entre as características dos veículos e o consumo de combustível. O peso e a potência apresentaram correlação negativa com o MPG, indicando que veículos mais pesados e com motores mais potentes tendem a apresentar menor eficiência nesse indicador.

Na comparação realizada no projeto, a rede neural MLP apresentou melhor desempenho nas métricas avaliadas. Já o sistema Fuzzy permite interpretar as previsões por meio de regras mais fáceis de entender.

## Arquivos do projeto

- `auto-mpg.csv`: base de dados utilizada na análise.
- `projeto_auto_mpg.ipynb`: notebook com o código, os gráficos e as etapas do trabalho.

## Tecnologias utilizadas

- Python
- Pandas e NumPy
- Matplotlib e Seaborn
- Scikit-learn
- scikit-fuzzy
- Jupyter Notebook

## Como executar

1. Baixe os arquivos deste repositório.
2. Instale as bibliotecas necessárias.
3. Abra `projeto_auto_mpg.ipynb` no Jupyter Notebook ou no Google Colab.
4. Execute as células na ordem apresentada.

O arquivo CSV deve permanecer acessível no mesmo ambiente em que o notebook for executado.

## Fonte dos dados

UCI Machine Learning Repository — Auto MPG Dataset

https://archive.ics.uci.edu/dataset/9/auto+mpg

## Autor

Kauã Kairon Alves de Melo

Projeto acadêmico de análise de dados e Inteligência Artificial.
