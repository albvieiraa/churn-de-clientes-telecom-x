# 📉 Telecom X - Análise de Evasão de Clientes

Este repositório contém uma análise exploratória dos dados de clientes da **Telecom X**, com o objetivo de entender os fatores que levam à evasão (churn). A análise serve como base para a equipe de Data Science desenvolver modelos preditivos e estratégias de retenção.

---

## 📌 Descrição do Desafio

A Telecom X enfrenta um alto índice de cancelamentos e precisa identificar os motivos por trás da saída dos clientes. Para isso, foi realizada uma análise baseada em dados reais, com foco em:

- Comportamento dos clientes
- Serviços contratados
- Tipos de contratos
- Cobranças mensais e diárias
- Correlações com o churn

---

## 📁 Estrutura do Projeto

- `telecomX_EDA_melhorado.ipynb`: Notebook principal com todas as etapas de limpeza, transformação e análise dos dados.
- `README.md`: Arquivo explicativo do projeto.

---

## ⚙️ Tecnologias e Bibliotecas

- Python 3.x
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Requests

---

## 🔍 Principais Análises Realizadas

- Distribuição de clientes que cancelaram vs. mantiveram o serviço
- Relação entre **cobrança diária** e churn
- Impacto da **quantidade de serviços contratados** na evasão
- Cálculo da **correlação** entre variáveis numéricas e churn
- Visualizações padronizadas em paleta verde-azulada (`BuGn`)

---

## 📊 Principais Insights

- **Clientes com menos serviços contratados** apresentaram maior taxa de churn.
- **Cobranças diárias mais altas** estão associadas a uma maior chance de evasão.
- Variáveis como tipo de contrato, suporte técnico e backup online mostram relação significativa com o churn.

---

## 🚀 Próximos Passos

- Construção de modelos preditivos para estimar a probabilidade de churn
- Criação de dashboards interativos com Streamlit ou Power BI
- Testes de estratégias de retenção baseadas nos insights extraídos

---

## 🧠 Autor

**Nome:** Maryllian Vieira  
**LinkedIn:** [[Maryllian Vieira](https://www.linkedin.com/in/maryllian-vieira-dev/)] 

---

## 📌 Observações

Os dados utilizados foram disponibilizados em formato `.json` por meio de uma API pública no GitHub.

---

## 📄 Licença

Este projeto está licenciado sob a licença MIT. Sinta-se à vontade para utilizar, modificar e distribuir, com os devidos créditos.

