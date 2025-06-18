# 📊 Análise de E-commerce com Foco em Churn Prediction

Este projeto tem como objetivo principal realizar uma **análise exploratória de dados** de um e-commerce, com foco na previsão de **churn** — ou seja, a **probabilidade de um cliente abandonar a plataforma**.

---

## 🗂️ Sobre o Projeto

A análise parte de um **dataset público com dados simulados** de uma plataforma de e-commerce. O processo incluiu:

- Limpeza e tratamento dos dados  
- Compreensão das variáveis  
- Análise exploratória  
- Desenvolvimento de um modelo de **Machine Learning (classificação)**

📌 **Objetivo do modelo:** Prever se um cliente irá ou não churnar (abandonar a plataforma), identificando as variáveis mais influentes no comportamento de saída.

---

## 📉 O que é Churn e por que ele importa?

**Churn** é um indicador estratégico, pois representa os clientes que **deixaram de utilizar a plataforma**. Monitorar essa métrica permite:

- Reduzir perdas financeiras 💸  
- Melhorar a experiência do usuário 😊  
- Criar estratégias mais eficientes de retenção 🔁

---

## 📊 Dashboard Interativo (Power BI)

A visualização foi desenvolvida em **Power BI**, dividida em dois painéis principais:

### 🧠 Painel 1: Visão Geral do Churn

#### Explicações e Indicadores:
- Dois cartões com o total de clientes que **churnaram** e **não churnaram**
- Gráfico de pizza com a **distribuição percentual do churn**
- Contextualização da variável `churn` e sua importância estratégica

#### 🔍 Análise do Perfil do Cliente
Variáveis analisadas em relação ao churn:
- `Gender`
- `MaritalStatus`
- `SatisfactionScore`

Todos representados por **gráficos de barras**, comparando churn e não churn.

> 📷 Abaixo, uma captura de tela do painel 1:
> ![image](https://github.com/user-attachments/assets/940b4767-2c6b-47d1-b661-5a3ee46ee3a6)

---

### 🔄 Painel 2: Comportamento e Engajamento

Neste painel, analisamos como o comportamento do cliente impacta no churn, utilizando:

- `Tenure` (tempo de relacionamento)
- `Complains` (reclamações)
- `WarehouseToHome` (distância da casa até o armazém)

Todos representados por **gráficos de barras**, comparando churn e não churn.

#### 🤖 Machine Learning - Feature Importance

O modelo de classificação foi treinado para prever o churn e entender quais variáveis têm maior influência.
Neste painel, optei por destacar a distribuição de importância de cada variável para o modelo.

📌 O gráfico de **Feature Importance** mostra as variáveis mais relevantes e pode ser visualizado abaixo com as demais análises:

> 📷 Captura de tela do painel 2:
![image](https://github.com/user-attachments/assets/1eeb54c3-285b-4f8d-8419-684343a54c55)

---
