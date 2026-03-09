# 📊 TelecomX — Previsão de Evasão de Clientes (Churn)

## 📌 Descrição do Projeto

Este projeto tem como objetivo prever a **evasão de clientes (churn)** da empresa fictícia TelecomX utilizando técnicas de **Machine Learning**. A análise busca identificar padrões que indicam maior probabilidade de cancelamento e entender quais fatores influenciam a retenção ou saída dos clientes.

---

# 🤖 Modelos de Classificação Utilizados

Foram treinados dois modelos de classificação:

* **Logistic Regression**
* **Random Forest**

## Resultados Obtidos

| Modelo              | Acurácia | Precisão (Churn) | Recall (Churn) | F1-score (Churn) |
| ------------------- | -------- | ---------------- | -------------- | ---------------- |
| Logistic Regression | **0.80** | 0.65             | **0.52**       | **0.58**         |
| Random Forest       | 0.78     | 0.62             | 0.48           | 0.54             |

A **Regressão Logística apresentou o melhor desempenho geral**, superando o Random Forest em todas as métricas avaliadas.

---

# 📏 Métricas de Avaliação

Os modelos foram avaliados utilizando as seguintes métricas:

* **Acurácia** – proporção total de previsões corretas
* **Precisão** – proporção de previsões de churn que estavam corretas
* **Recall** – capacidade do modelo de identificar clientes que realmente cancelaram
* **F1-score** – média harmônica entre precisão e recall
* **Matriz de Confusão** – análise dos acertos e erros do modelo

Essas métricas permitem avaliar não apenas a precisão geral do modelo, mas também sua capacidade de identificar clientes com risco de cancelamento.

---

# 🔎 Principais Fatores que Aumentam o Churn

A análise de importância das variáveis identificou alguns fatores associados ao aumento da evasão de clientes:

* **Internet Fiber Optic**
* **Pagamento via Electronic Check**
* **Paperless Billing**
* **Clientes idosos (SeniorCitizen)**
* **Clientes com menor tempo de contrato**

Esses fatores indicam perfis de clientes com maior probabilidade de cancelar o serviço.

---

# 🟢 Fatores Associados à Retenção de Clientes

Algumas variáveis demonstraram forte relação com **menor probabilidade de churn**:

* **Contratos de longo prazo (1 ou 2 anos)**
* **Maior tempo de relacionamento com a empresa (tenure)**
* **Serviços adicionais como Online Security e Tech Support**
* **Clientes com dependentes ou parceiros**

Essas características indicam maior engajamento e fidelização com o serviço.

---

# 📊 Conclusão

Os modelos desenvolvidos foram capazes de identificar padrões relevantes associados à evasão de clientes.

Entre os modelos testados, a **Logistic Regression apresentou melhor desempenho**, atingindo **80% de acurácia** e demonstrando boa capacidade de identificar clientes com risco de churn.

A análise das variáveis mostrou que fatores como **tipo de contrato, tempo de relacionamento com a empresa, método de pagamento e serviços adicionais** têm forte influência na decisão de cancelamento.

Esses resultados demonstram como técnicas de **Machine Learning aplicadas a dados de clientes** podem ajudar empresas a compreender melhor o comportamento de seus usuários e identificar clientes com maior risco de evasão.
