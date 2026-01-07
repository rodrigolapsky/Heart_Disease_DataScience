# 🩺 Heart Disease Prediction: End-to-End Data Science

Este projeto de Ciência de Dados para a predição de doenças cardíacas, desde a análise exploratória até a implementação de modelos de Machine Learning.

## 🚀 O Projeto
O objetivo principal foi construir um modelo capaz de identificar riscos cardíacos com precisão. 
O pipeline incluiu:
* **Pré-processamento:** Normalização com `MinMaxScaler` e tratamento de classes desbalanceadas com **SMOTE**.
* **Modelagem:** Comparação entre múltiplos algoritmos (Logistic Regression, Random Forest, XGBoost, LightGBM, SVM, Redes Neurais MLP).
* **Otimização:** Ajuste de hiperparâmetros via `GridSearchCV` e `RandomizedSearchCV`.

## 📊 Resultados e Performance
O modelo foi validado com dados de teste para garantir resultados reais e confiáveis:
* **Acurácia de Teste:** 97,95%
* **Destaque:** Utilização de Matriz de Confusão para análise de Falsos Negativos, essencial para a área da saúde.

## 🛠️ Stack Tecnológica (Bibliotecas Utilizadas)
* **Manipulação:** `Pandas`, `NumPy`
* **Visualização:** `Seaborn`, `Matplotlib`
* **Machine Learning:** `Scikit-Learn`, `XGBoost`, `LightGBM`
* **Balanceamento:** `Imbalanced-learn` (SMOTE)



