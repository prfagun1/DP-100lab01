# 📈 Análise Preditiva de Vendas de Sorvetes

Este projeto tem como objetivo aplicar técnicas de **ciência de dados** e **aprendizado de máquina** para prever as vendas de sorvetes com base em variáveis climáticas, como temperatura, umidade e estação do ano. É uma simulação prática para fixar os conhecimentos adquiridos no curso **DP-100: Designing and Implementing a Data Science Solution on Azure**.

## 🎯 Objetivo

Desenvolver um modelo preditivo capaz de estimar a quantidade de sorvetes vendidos em determinado dia, considerando fatores ambientais.

## 🧰 Tecnologias e Ferramentas

- Python
- Pandas
- Scikit-learn
- Matplotlib & Seaborn
- Jupyter Notebook
- Azure Machine Learning (simulado/local)

## 🧪 Etapas do Projeto

### 1. Coleta e Entendimento dos Dados
Utilizamos um dataset fictício contendo colunas como:
- `Temperatura`
- `Umidade`
- `Dia da Semana`
- `Estação`
- `Vendas de Sorvete`

### 2. Análise Exploratória
- Correlações observadas entre temperatura e vendas.
- Visualizações como scatter plots e heatmaps ajudaram a entender os padrões.

### 3. Preparação dos Dados
- Tratamento de valores nulos.
- Codificação de variáveis categóricas.
- Divisão entre treino e teste.

### 4. Criação do Modelo
Pode ser utilizado o algoritmo **Regressão Linear**, por ser simples e eficaz para problemas com relação direta entre variáveis numéricas.

### 5. Avaliação do Modelo


## 📊 Resultados

Abaixo um exemplo de previsão:

| Temperatura | Estação   | Vendas Previstas |
|-------------|-----------|------------------|
| 32°C        | Verão     | 110 unidades     |
| 20°C        | Outono    | 52 unidades      |


## 🚀 Possibilidades Futuras

- Utilizar algoritmos mais robustos como **Random Forest** ou **XGBoost**.
- Integrar com dados meteorológicos em tempo real via API.
- Implantar em um endpoint no Azure Machine Learning para consumo em apps web.

