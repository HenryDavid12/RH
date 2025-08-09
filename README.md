
# Projeto de Previsão de Rotatividade (Attrition)

## Visão Geral

Este projeto tem como objetivo analisar e prever a rotatividade de funcionários em uma organização utilizando técnicas de análise exploratória e modelagem preditiva com XGBoost. A previsão do risco de desligamento permite que o RH tome decisões mais assertivas para reduzir custos e impactos negativos associados à saída de colaboradores.

## Problema de Negócio

A rotatividade de funcionários gera custos elevados, perda de conhecimento e impacto na produtividade. Identificar os principais fatores que levam à saída e prever colaboradores em risco é essencial para implementar estratégias eficazes de retenção.

## Objetivos

- Entender os padrões e características dos funcionários que saem.
- Construir um modelo preditivo para estimar a probabilidade de desligamento.
- Apresentar insights estratégicos para apoiar decisões de RH.

## Análise Exploratória

- Avaliação da rotatividade por departamento, cargo, faixa salarial e satisfação.
- Identificação de áreas com maior rotatividade: Research e Sales.
- Profissões com maior risco: Laboratory Technician, Sales Executive, Research Scientist, Sales Representative.
- Variáveis chave associadas à saída: métricas de satisfação, salário e overtime.

## Modelagem Preditiva

- Algoritmo utilizado: XGBoost.
- Métricas principais:  
  - Classe 0 (Não saiu): Precision 0.88, Recall 0.98, F1 0.93  
  - Classe 1 (Saiu): Precision 0.78, Recall 0.30, F1 0.43
- Ajustes de threshold para melhorar sensibilidade.
- Limitações identificadas relacionadas ao desbalanceamento de classes.

## Resultados e Insights

- Modelo com alta capacidade para identificar colaboradores estáveis.
- Aumento da rotatividade associada a cargos e departamentos específicos.
- Baixa satisfação e salário abaixo da média são fortes preditores.
- Overtime frequente eleva o risco de desligamento.

## Dashboard

- Visualização interativa dos principais KPIs.
- Página adicional dedicada às variáveis preditivas e riscos calculados.
- Segmentação por departamentos, cargos e níveis de risco.

## Tecnologias e Ferramentas

- Linguagem: Python (pandas, scikit-learn, xgboost, matplotlib, seaborn)
- Modelagem e análise: XGBoost, análise de métricas, tratamento de dados.
- Visualização: Power BI para dashboards e apresentação.

## Estrutura do Projeto

 



