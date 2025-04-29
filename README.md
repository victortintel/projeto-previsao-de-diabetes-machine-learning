# Projeto de Machine Learning: Previsão de Diabetes

Este projeto tem como objetivo desenvolver um modelo de machine learning para prever diabetes em pacientes com base em diversas características de saúde. Utilizamos o dataset Pima Indians Diabetes, que é um conjunto de dados clássico para problemas de classificação binária.

## 📌 Visão Geral

O projeto segue todas as etapas de um fluxo de trabalho completo de ciência de dados:
1. Análise Exploratória de Dados (EDA)
2. Pré-processamento e Engenharia de Atributos
3. Modelagem com vários algoritmos (Regressão Logística, Árvore de Decisão, Random Forest, KNN, SVM, XGBoost, Naive Bayes)
4. Otimização de Hiperparâmetros
5. Interpretação do Modelo e Insights

## 📊 Principais Resultados

- O modelo final (XGBoost otimizado) alcançou uma AUC ROC de 0.83 no conjunto de teste.
- As features mais importantes foram Glicose, IMC e Idade.
- O modelo pode identificar corretamente 75% dos casos de diabetes (recall) com uma precisão de 70%.

## 🛠️ Tecnologias Utilizadas

- Python 3
- Jupyter Notebook
- Bibliotecas: pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost, shap
