# 🚀 Projeto Capstone: Prevendo o Sucesso de Lançamentos da SpaceX

Este repositório contém o projeto final de conclusão do [**Certificado Profissional IBM Data Science**](https://www.coursera.org/professional-certificates/ibm-data-science) da Coursera.

## 🎯 Objetivo do Projeto

O objetivo deste projeto é construir um pipeline completo de ciência de dados para prever se um lançamento de foguete Falcon 9 da SpaceX será bem-sucedido (resultando em um pouso bem-sucedido do primeiro estágio). O projeto cobre todas as etapas, desde a coleta de dados de múltiplas fontes até a construção de um modelo de machine learning preditivo e a criação de um dashboard interativo.

---

## 🛠️ Stack de Ferramentas

* **Linguagem:** Python
* **Análise e Manipulação de Dados:** Pandas, NumPy
* **Coleta de Dados:** BeautifulSoup (Web Scraping), API REST (SpaceX API)
* **Análise Exploratória de Dados (EDA):** SQL (com SQLite), Matplotlib, Seaborn
* **Visualização Geoespacial:** Folium
* **Machine Learning:** Scikit-learn (Logistic Regression, SVM, Decision Trees, KNN)
* **Dashboard:** Plotly Dash

---

## 📖 Estrutura do Projeto (O Pipeline)

Os arquivos neste repositório seguem o fluxo de trabalho de ciência de dados ensinado no curso. Cada notebook representa uma etapa do pipeline:

### 1. Coleta de Dados (Data Collection)
* **`jupyter-labs-webscraping.ipynb`**: Realiza web scraping de uma tabela do Wikipedia com o histórico de lançamentos do Falcon 9.
* **`jupyter-labs-spacex-data-collection-api.ipynb`**: Coleta dados adicionais e mais granulares diretamente da API pública da SpaceX.

### 2. Limpeza e Pré-processamento (Data Wrangling)
* **`jupyter-labs-spacex-Data wrangling.ipynb`**: Unifica os dados das duas fontes (API e scraping), limpa valores ausentes, corrige tipos de dados e prepara o dataset para a análise.

### 3. Análise Exploratória de Dados (EDA) com SQL
* **`jupyter-labs-eda-sql-coursera_sqlite.ipynb`**: Carrega o dataset limpo em um banco de dados SQLite e utiliza consultas SQL para realizar análises exploratórias e responder perguntas de negócio iniciais.

### 4. Análise Exploratória de Dados (EDA) com Visualização
* **`lab_jupyter_launch_site_location.ipynb`**: Utiliza a biblioteca Folium para plotar os locais de lançamento da SpaceX em um mapa interativo, analisando visualmente a relação entre o local e a taxa de sucesso.
* **`edataviz.ipynb`**: Aprofunda a EDA utilizando Matplotlib e Seaborn para analisar a relação entre as features (como `PayloadMass`, `Orbit`, etc.) e a taxa de sucesso.

### 5. Engenharia de Features e Modelagem Preditiva
* **`SpaceX_Machine_Learning_Prediction_Part_5.ipynb`**: Realiza a engenharia de features (ex: One-Hot Encoding das variáveis categóricas) e prepara os dados para o treinamento.
* **`Logistic-Regression-v1.ipynb`**: Testa e avalia diversos modelos de classificação (Regressão Logística, SVM, Árvore de Decisão, KNN) para encontrar o modelo com melhor performance na previsão de sucesso do lançamento.

### 6. Dashboard Interativo
* **`Dashboard code with plot`**: Script em Plotly Dash que cria um dashboard interativo para visualizar os resultados dos lançamentos e as taxas de sucesso.

---

## 📈 Resultados do Modelo de Machine Learning

Após o treinamento e teste de múltiplos algoritmos de classificação, o modelo Árvore de Decisão (Decision Tree) alcançou a melhor performance, com uma acurácia de 91% no conjunto de testes. 

* **`Capstone Project IBM Data Science.pdf`**: O arquivo com a apresentação dos resultados e eplicação da metodologia utilizada.

## 🎓 Certificado

* **[Link para o Certificado no Coursera](https://coursera.org/share/fa64e3ae11e03bc02b8a2e1df229420d)**
