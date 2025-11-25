# Trabalho de Inteligência Artificial - Classificação

Este projeto refere-se à parte de **Classificação** do trabalho prático da disciplina **ECOM08A – Inteligência Artificial**, ministrada pelo Prof. João Paulo R. R. Leite na UNIFEI.

## Integrantes

- João Pedro Quintero Cabral - 2023001479
- Lucas Galvão Freitas - 2023001147

## Descrição do Trabalho

O objetivo deste trabalho é aplicar diferentes algoritmos de aprendizado de máquina para resolver um problema de classificação. O desenvolvimento segue as etapas fundamentais de um projeto de Data Science:

1. **Carregamento dos dados**: Leitura do dataset `Healthcare-Diabetes.csv`.
2. **Limpeza e Pré-processamento**: Tratamento de valores nulos (substituição pela mediana), análise de outliers e normalização (RobustScaler).
3. **Análise Exploratória**: Visualização das relações entre as variáveis de entrada e a variável alvo.
4. **Treinamento e Teste**: Divisão dos dados e treinamento dos modelos.
5. **Avaliação e Comparação**: Análise de métricas e discussão sobre a generalização dos modelos.

## Dataset

O conjunto de dados utilizado é o **Healthcare-Diabetes**, que contém medidas diagnósticas para prever se um paciente tem ou não diabetes.

- **Arquivo**: `Healthcare-Diabetes.csv`

## Modelos Implementados

Conforme os requisitos do trabalho, foram implementados e comparados os seguintes algoritmos:

- **Regressão Logística** (Logistic Regression)
- **Árvore de Decisão** (Decision Tree)
- **SVM** (Support Vector Machine)
- **MLP** (Multilayer Perceptron / Rede Neural)

## Métricas de Avaliação

Para avaliar a performance de cada classificador, foram utilizadas as métricas:

- Acurácia (Requisito mínimo: > 75%)
- Precisão
- Recall
- F1-Score
- Matriz de Confusão

## Como Executar

1. Certifique-se de ter o Python instalado.
2. Instale as dependências necessárias:
   ```bash
   pip install -r requirements.txt
   ```
3. Abra e execute o notebook `classification_notebook.ipynb` em seu ambiente de preferência (VS Code, Jupyter Lab, etc).

---
