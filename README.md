# Predict_Churn-Telco

## Índice
- [Conjunto de Dados](#conjunto-de-dados)
- [Problema de Negócio](#problema-de-negócio)
- [Objetivos do Projeto](#objetivos-do-projeto)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Modelos e Validação](#modelos-e-validação)
- [Conclusão](#conclusão)

## Conjunto de Dados
Os dados utilizados neste projeto são fictícios e foram obtidos do [Kaggle - Telco Customer Churn](https://www.kaggle.com/telco-customer-churn).

## Problema de Negócio
Uma empresa de telecomunicações busca compreender e reduzir o churn, isto é, a evasão de clientes — um dos maiores desafios do setor.

## Objetivos do Projeto
- Gerar insights por meio de análise exploratória de dados que possam ajudar na redução do churn.
- Utilizar técnicas de Machine Learning para prever quais clientes têm maior probabilidade de deixar a empresa.

## Estrutura do Projeto
- **Importação de Bibliotecas:** Pacotes e módulos essenciais para análise e modelagem.
- **Limpeza dos Dados:** Tratamento de valores ausentes, inconsistências e outliers.
- **Análise Exploratória de Dados (EDA):** Visualização, geração de novas variáveis e análise de padrões.
- **Processamento dos Dados:** Criação de variáveis dummies, padronização, e divisão dos dados em treino e teste.
- **Modelagem de Machine Learning:**
  - Teste de diferentes modelos;
  - Ajuste de hiperparâmetros utilizando validação cruzada (cross-validation);
  - Comparação de performance de modelos.

## Modelos e Validação
Os seguintes modelos de Machine Learning foram aplicados utilizando busca por hiperparâmetros e validação cruzada para garantir resultados robustos:

- **XGBoost**
- **Regressão Logística**
- **Random Forest**

A otimização foi realizada através de técnicas como Grid Search (busca em grade), com o objetivo de maximizar os principais indicadores de desempenho, especialmente a métrica AUC-ROC, relevante na avaliação de modelos de churn.

## Conclusão
Foram comparados diferentes modelos de Machine Learning, validados com rigor estatístico, permitindo identificar a abordagem mais eficiente para prever e reduzir o churn de clientes de uma empresa de telecomunicações.

---

Se desejar adicionar instruções de execução, dependências, exemplos de uso ou outro tópico, posso complementar.
