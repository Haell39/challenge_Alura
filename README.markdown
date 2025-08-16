# Análise de Evasão de Clientes (Churn) - Telecom X

## 📄 Resumo do Projeto

Este projeto realiza uma análise exploratória de dados (EDA) da base de clientes da Telecom X, com foco em identificar fatores que influenciam a evasão de clientes (churn). O objetivo é gerar insights para estratégias de retenção, como parte do desafio do Programa ONE (Oracle Next Education) com a Alura.

## 🎯 Contexto

A Telecom X enfrenta alta taxa de churn sem clareza sobre suas causas. O projeto envolve ETL e EDA para orientar modelos preditivos.

## 📁 Estrutura

- **data/**: `TelecomX_Data.json` (dados brutos)
- **images/**: Gráficos gerados (opcional)
- **README.md**: Documentação
- **requirements.txt**: Dependências
- **Analise_Churn_TelecomX.ipynb**: Notebook com a análise

## 🛠️ Tecnologias

- **Linguagem**: Python 3
- **Bibliotecas**: pandas, numpy, matplotlib, seaborn
- **Ambiente**: Jupyter Notebook

## Alguns gráficos e insights

A análise dos dados revelou um perfil claro para os clientes com maior probabilidade de cancelar o serviço (Churn). Os gráficos abaixo destacam as principais tendências demográficas e financeiras que sustentam nossas conclusões.

![Análise de Churn por variáveis numéricas](imgs/image.png)

![Análise de Churn por perfil democrático](imgs/image2.png)

### Perfil do Cliente com Alto Risco de Evasão:

- **Tempo de Contrato:** É um cliente **novo**, com poucos meses de serviço (`tenure`). A lealdade aumenta drasticamente com o tempo.
- **Custo do Serviço:** Paga uma **fatura mensal elevada** (`MonthlyCharges`), sugerindo alta sensibilidade ao preço.
- **Perfil Demográfico:** Geralmente é um cliente **idoso (`SeniorCitizen`)** e que **não possui parceiro(a) ou dependentes**, indicando menor vínculo familiar e, possivelmente, maior flexibilidade para trocar de provedor.

## ⚙️ Instalação

1. Clone o repositório:
   ```bash
   git clone https://[URL-DO-REPOSITORIO]
   cd challenge-data-science
   ```
2. Crie um ambiente virtual:
   ```bash
   python -m venv venv
   source venv/bin/activate  # Windows: venv\Scripts\activate
   ```
3. Instale dependências:
   ```bash
   pip install -r requirements.txt
   ```

## 🚀 Execução

1. Inicie o Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
2. Abra e execute o arquivo `Analise_Churn_TelecomX.ipynb`.
