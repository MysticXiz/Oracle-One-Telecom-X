# 🚀 Projeto: Análise de Evasão de Clientes (Churn) - Telecom X

Este projeto foi desenvolvido como parte de um desafio de Data Science para identificar padrões e fatores que levam ao cancelamento de clientes na empresa **Telecom X**.

## 📋 Objetivo
Realizar o processo de **ETL (Extração, Transformação e Carga)** e uma **Análise Exploratória de Dados (EDA)** para extrair insights estratégicos que ajudem a reduzir o índice de evasão.

## 🛠️ Tecnologias Utilizadas
- **Python 3**
- **Pandas**: Manipulação e tratamento de dados.
- **Requests**: Coleta de dados via API.
- **Matplotlib & Seaborn**: Visualização de dados e gráficos estatísticos.

## 📂 Estrutura do Projeto
O notebook está organizado nas seguintes etapas:
1. **Extração**: Consumo dos dados brutos em formato JSON direto do GitHub.
2. **Transformação**: Limpeza de dados, conversão de tipos (ex: `TotalCharges`) e tratamento de valores ausentes.
3. **Carga e Análise**: Exploração visual dos dados focada em variáveis categóricas e numéricas que influenciam o Churn.
4. **Relatório Final**: Consolidação de insights e recomendações de negócio.

## 🚀 Como Executar
1. Execute as células em ordem sequencial.
2. Certifique-se de ter conexão com a internet para que a biblioteca `requests` consiga baixar o dataset.
3. As visualizações serão geradas automaticamente na seção de Análise.
