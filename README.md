# 🏦 CreditAI: Sistema de Análise de Risco de Crédito

![Status](https://img.shields.io/badge/Status-Concluído-green)
![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Lib](https://img.shields.io/badge/Lib-Scikit--Learn-orange)

## Sobre o Projeto
Este projeto é um **Sistema de Suporte à Decisão** desenvolvido para automatizar a concessão de empréstimos pessoais em uma Fintech simulada. O modelo utiliza algoritmos de Machine Learning para classificar clientes entre **Aprovados** e **Reprovados (Risco)**.

O objetivo foi cobrir todo o ciclo de Ciência de Dados: desde a simulação de dados realistas até a regularização de modelos para evitar overfitting.

## Regras de Negócio (O Diferencial)
Diferente de datasets comuns, este projeto simula regras financeiras rígidas:
* **Taxa de Juros:** 4,96% ao mês (Tabela Price).
* **Margem Consignável:** A parcela não pode ultrapassar **35% da renda líquida**.
* **Compliance:** Score baixo e negativação têm peso crítico na decisão.

## Tecnologias Utilizadas
* **Linguagem:** Python
* **Bibliotecas:** Pandas, Numpy, Matplotlib, Seaborn.
* **Machine Learning:** Scikit-Learn (Decision Tree & Logistic Regression).
* **Ambiente:** Jupyter Notebook / Google Colab.

## Resultados Principais
O modelo final (Árvore de Decisão Regularizada) atingiu:
* **Alta Acurácia:** > 90% de acertos globais.
* **Segurança:** Minimização de Falsos Negativos (evitando aprovar caloteiros).
* **Interpretabilidade:** O ranking de features confirmou que *Score Serasa* e *Histórico de Negativação* são os fatores mais determinantes.

## Como Executar
1.  Clone este repositório ou baixe o arquivo `.ipynb`.
2.  Abra no Google Colab ou Jupyter Notebook.
3.  Execute todas as células para gerar a simulação de dados e treinar o modelo em tempo real.

---
**Desenvolvido por:** Thayná Assis
*Projeto Final da Disciplina de Machine Learning*
