TelecomX - Parte 2: Previsão de Churn

Objetivo
Construir modelos preditivos para identificar clientes com maior risco de evasão (churn) utilizando dados tratados da Parte 1 do desafio TelecomX.

Dados
- `dados_tratados.csv`: Dataset já limpo e pré-processado, contendo variáveis demográficas, serviços contratados e históricos de cobrança.

Estrutura do projeto
- `telecom_x_parte2.ipynb`: Notebook com todo o processo de análise, modelagem, avaliação e visualização.
- `dados_tratados.csv`: Dados utilizados para treino e teste dos modelos.

Metodologia
1. Carregamento e preparação dos dados.
2. Codificação de variáveis categóricas (One-Hot Encoding).
3. Divisão em conjunto de treino e teste (80/20).
4. Normalização das variáveis numéricas.
5. Treinamento e avaliação de modelos preditivos (Regressão Logística e Random Forest).
6. Análise da importância das variáveis.
7. Visualizações exploratórias para insights.

Resultados
- Acurácia da Regressão Logística: ~79%.
- Principais fatores que impactam churn: `Charges.Total`, `tenure`, `Charges.Monthly`, tipo de contrato e forma de pagamento.
- Clientes com contratos mensais e pagamento via cheque eletrônico têm maior risco de churn.

Como executar
1. Instale as dependências necessárias (ex: pandas, scikit-learn, matplotlib, seaborn).
2. Abra o notebook `telecom_x_parte2.ipynb`.
3. Execute as células na ordem para reproduzir a análise.

Projeto desenvolvido como parte do desafio TelecomX — Especialização em Data Science.
