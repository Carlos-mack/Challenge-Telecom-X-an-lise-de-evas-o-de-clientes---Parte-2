# TelecomX-Parte-2
# 📊 TelecomX – Previsão de Churn de Clientes

[![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Carlos-mack/Challenge-Telecom-X-an-lise-de-evas-o-de-clientes---Parte-2/blob/main/Challenge_TelecomX_2.ipynb)

## 📌 Sobre o Projeto
Este projeto tem como objetivo desenvolver um modelo de Machine Learning capaz de prever, com antecedência, quais clientes da **TelecomX** apresentam maior probabilidade de cancelar o serviço (**churn**).  
A iniciativa busca apoiar a empresa na criação de **estratégias de retenção** mais eficientes, reduzindo a evasão e aumentando a fidelização da base de clientes.

---

## 🎯 Objetivos
- Analisar dados históricos de clientes da TelecomX.
- Identificar variáveis mais relevantes para a previsão de churn.
- Tratar o desequilíbrio de classes (clientes que cancelaram vs. clientes que permaneceram).
- Treinar e comparar modelos de Machine Learning.
- Selecionar o modelo mais robusto para aplicação prática.

---

## 📂 Estrutura do Projeto

---

## ⚙️ Metodologia

### 1️⃣ Preparação e Limpeza dos Dados
- Remoção de colunas irrelevantes
- Padronização e tratamento de valores nulos
- Codificação de variáveis categóricas (One-Hot Encoding)

### 2️⃣ Análise Exploratória
- Análise da proporção de churn
- Correlação entre variáveis
- Visualizações (heatmaps, boxplots, scatter plots)

### 3️⃣ Balanceamento de Classes
- Uso da técnica **SMOTE** para corrigir desbalanceamento

### 4️⃣ Modelagem
Modelos testados:
- **Regressão Logística** (com normalização)
- **Random Forest** (sem normalização)

### 5️⃣ Avaliação
- Métricas: Acurácia, Precisão, Recall, F1-Score
- Matriz de confusão
- Validação cruzada

---

## 📈 Principais Resultados
- O modelo **Random Forest** apresentou melhor equilíbrio entre **Recall** e **Precisão**.
- Fatores mais relacionados ao churn:
  - Contratos mensais sem fidelização
  - Tempo de contrato curto
  - Baixo gasto total
  - Falta de serviços adicionais

---

## 🚀 Tecnologias Utilizadas
- **Python**  
- **Pandas**, **NumPy**, **Matplotlib**, **Seaborn**  
- **Scikit-learn**  
- **Imbalanced-learn (SMOTE)**  
- **Jupyter Notebook**

---

## 📌 Próximos Passos
- Implementar o modelo em ambiente de produção.
- Integrar previsões ao CRM da empresa.
- Coletar novas variáveis (ex.: histórico de suporte, satisfação do cliente).
- Realizar monitoramento contínuo da performance.

---



