# 📊 Telecom X — Análise de Evasão de Clientes (Churn)

Este repositório apresenta a solução de um **desafio de Ciência de Dados da Alura**, cujo objetivo é analisar e compreender os fatores que influenciam a evasão de clientes (*churn*) em uma empresa fictícia de telecomunicações, a **Telecom X**.

## 🎯 Objetivo
Identificar padrões e variáveis relevantes associadas ao cancelamento de clientes, fornecendo subsídios para o desenvolvimento de modelos preditivos e estratégias de retenção.

## 🧩 Etapas do Projeto
- Extração de dados a partir de uma API (formato JSON)
- Limpeza, transformação e preparação dos dados (ETL)
- Análise Exploratória de Dados (EDA)
- Tratamento de variáveis categóricas (One-Hot Encoding)
- Avaliação de desbalanceamento das classes
- Construção e avaliação de modelos de Machine Learning
- Análise de importância das variáveis

## 🤖 Modelos Utilizados
- **Regressão Logística** (com normalização)
- **Random Forest** (sem necessidade de normalização)

Os modelos foram avaliados utilizando:
- Acurácia
- Precisão
- Recall
- F1-score
- Matriz de confusão

## 📈 Principais Insights
- O tempo de permanência do cliente (*tenure*) é um dos fatores mais relevantes para a evasão.
- Contratos mensais apresentam maior risco de churn.
- Valores de cobrança mensal elevados estão associados a maior probabilidade de cancelamento.
- Serviços adicionais, como suporte técnico e segurança online, reduzem a evasão.

## 🛠️ Tecnologias e Bibliotecas
- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn
- Imbalanced-learn

## 📁 Estrutura do Repositório
- `notebooks/` → Análises e experimentos
- `data/` → Base de dados utilizada
- `README.md` → Descrição do projeto

## 📌 Observações
Este projeto tem caráter **educacional**, sendo parte de um desafio proposto pela **Alura**, com foco no aprendizado prático de análise de dados e machine learning aplicado a problemas reais de negócio.

---
📚 *Desenvolvido como parte da formação em Ciência de Dados — Alura*
