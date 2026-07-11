# Predição de Churn para Apoiar Estratégias de Retenção de Clientes

## Visão Geral

Empresas de telecomunicações perdem receita quando clientes cancelam seus serviços. No entanto, agir somente após o cancelamento impede qualquer ação preventiva.

Neste projeto foi desenvolvido um modelo preditivo capaz de identificar clientes com maior probabilidade de evasão, permitindo que equipes de Marketing, CRM e Customer Success priorizem ações de retenção antes que o cancelamento aconteça.

Além da construção do modelo, o projeto analisa quais características mais influenciam o comportamento dos clientes, transformando previsões em recomendações para o negócio.

## Problema de Negócio

A empresa precisava responder duas perguntas:

Quais clientes apresentam maior risco de cancelar o serviço?
Quais fatores mais influenciam essa decisão?

Responder essas perguntas permite direcionar campanhas de retenção para os clientes certos, reduzindo custos e aumentando a eficiência das ações comerciais.

## Solução Desenvolvida

O projeto contemplou todo o fluxo de construção de um modelo preditivo:

- Preparação e tratamento dos dados
- Engenharia de atributos (Feature Engineering)
- Codificação de variáveis categóricas
- Divisão entre conjuntos de treino e teste
- Treinamento de diferentes algoritmos de classificação
- Comparação entre modelos
- Avaliação utilizando métricas adequadas para problemas de churn
- Interpretação das variáveis mais importantes para o modelo

## Modelos Avaliados

Foram comparados dois algoritmos de classificação:

Modelo	Objetivo
Logistic Regression	Modelo interpretável para compreender o impacto das variáveis
Random Forest	Modelo baseado em árvores para capturar relações não lineares

Após os testes, a Regressão Logística apresentou o melhor desempenho geral, oferecendo melhor equilíbrio entre capacidade preditiva e interpretabilidade.

### Resultados
Modelo	Acurácia	Precisão	Recall	F1-score
Logistic Regression	0.80	0.65	0.52	0.58
Random Forest	0.78	0.62	0.48	0.54

Embora ambos tenham apresentado resultados próximos, a Regressão Logística foi escolhida por combinar melhor desempenho e facilidade para interpretar os fatores associados ao churn.

# Principais Descobertas
Clientes em contratos mensais apresentam maior risco

O tipo de contrato foi uma das variáveis mais relevantes para prever cancelamentos.

## Possível ação

- Incentivar migração para contratos anuais.
- Criar campanhas específicas para clientes recém-adquiridos.
- Tempo de relacionamento reduz significativamente o risco

**Clientes com maior tempo de permanência tendem a permanecer ativos.**

### Possível ação

- Intensificar estratégias de retenção durante os primeiros meses do relacionamento.
- Serviços adicionais aumentam retenção

Clientes que utilizam serviços como Online Security e Tech Support apresentaram menor probabilidade de cancelar.

### Possível ação

- Desenvolver campanhas de cross-sell para clientes novos.
- Método de pagamento influencia o comportamento

**Clientes que utilizam Electronic Check apresentaram maior probabilidade de churn.**

### Possível ação

Investigar possíveis fricções no processo de pagamento.
Incentivar métodos com maior retenção.

## Como este projeto pode apoiar uma empresa

*Este tipo de solução pode ser utilizado para:*

- Priorizar clientes com maior risco de cancelamento.
- Apoiar campanhas de retenção.
- Direcionar ações de Customer Success.
- Reduzir perdas de receita.
- Identificar perfis de clientes com maior risco.
- Apoiar decisões estratégicas baseadas em dados.

## Tecnologias Utilizadas
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Jupyter Notebook

## Competências Demonstradas

**Este projeto demonstra experiência prática em:**

Limpeza e preparação de dados

Engenharia de atributos

Modelagem preditiva

Avaliação de modelos de Machine Learning

Interpretação de métricas de classificação

Tradução de resultados técnicos em recomendações de negócio

Comunicação de insights para tomada de decisão

***Este projeto é a continuação da análise exploratória realizada no projeto TelecomX - Parte 1. Após identificar os fatores associados ao churn, esta etapa utiliza Machine Learning para prever quais clientes apresentam maior probabilidade de cancelar o serviço.***
