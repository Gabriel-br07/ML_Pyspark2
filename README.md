# Projeto de Modelagem de Churn com PySpark
Este repositório contém o código e os passos envolvidos na construção de um modelo de machine learning para prever se um cliente vai se tornar churn (cancelar o serviço) ou não. O desafio foi enfrentado utilizando a ferramenta PySpark, uma escolha deliberada para explorar uma tecnologia nova e desafiadora.

## Objetivo do Projeto
O objetivo principal era criar um modelo de regressão logística capaz de classificar clientes como churn ou não churn com base em dados históricos e informações pessoais dos clientes, como tipo de contrato e outros atributos relevantes.

## Tecnologias Utilizadas
PySpark: Ferramenta de processamento de big data para manipulação e análise eficientes de grandes conjuntos de dados.
Spark MLlib: Biblioteca de machine learning integrada ao Spark para treinamento e avaliação de modelos.
Outras bibliotecas Python: Utilizamos bibliotecas padrão como NumPy e pandas para manipulação de dados.
## Etapas do Projeto
### 1 - Exploração e Tratamento dos Dados:

* Leitura dos dados usando PySpark.
* Tratamento de variáveis categóricas através da criação de dummies para facilitar a interpretação do modelo.
### 2 - Modelo de Regressão Logística:

* Entendimento e implementação do modelo de regressão logística no contexto do PySpark.
* Preparação dos dados em formato de vetor para alimentar o modelo.
### 3 - Avaliação do Modelo Inicial:

* Criação de métricas de avaliação, incluindo a matriz de confusão.
* Exploração de outros algoritmos de machine learning disponíveis no Spark.
### 4 - Árvore de Decisão e Floresta Aleatória:

* Implementação e avaliação de uma árvore de decisão no contexto do Spark.
* Exploração da floresta aleatória como uma alternativa.
### 5 - Otimização de Hiperparâmetros:

* Utilização de ferramentas do Spark para otimização de hiperparâmetros, incluindo validação cruzada.
### 6 - Escolha do Melhor Modelo:

* Reflexão sobre métricas importantes e tomada de decisão sobre o modelo ideal.
### 7 - Treinamento do Modelo Final:

* Aplicação da otimização de hiperparâmetros ao modelo escolhido, utilizando toda a base de dados.
### 8 - Teste com Novos Dados:

* Classificação de um novo cliente não visto pelo modelo para simular o comportamento em produção.
