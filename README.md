# 📊 Dashboard Financeiro | Power BI

Projeto desenvolvido com foco em análise estratégica de dados financeiros, utilizando Power BI para construção de visualizações interativas e geração de insights de negócio.

---

## 🚀 Objetivo

Construir um dashboard capaz de apoiar a tomada de decisão a partir de indicadores financeiros, permitindo:

- Monitoramento de receita, custos, despesas e lucro  
- Análise temporal (mensal)  
- Avaliação de performance por cliente  
- Identificação de padrões e oportunidades  

---

## 📷 Preview do Dashboard

### 📌 Visão Geral
![Visão Geral](/Images/Visao_Geral.PNG)

### 📌 Detalhamento
![Detalhamento](/Images/Detalhamento.PNG)

---

## 🧩 Modelagem de Dados

O projeto foi estruturado utilizando o modelo **Star Schema (Esquema Estrela)**, garantindo melhor performance e organização analítica.

### 🔹 Tabela Fato
- `f_financeiro`
  - receita  
  - custo  
  - despesa  
  - data  
  - id_cliente  

### 🔹 Tabelas Dimensão
- `d_calendario` → suporte a análises temporais  
- `d_cliente` → segmentação por cliente  

---

## 📊 Principais Métricas (KPIs)

- 💰 Receita Total  
- 💸 Custos  
- 📉 Despesas  
- 📈 Lucro  
- 📊 Margem de Lucro (%)  
- 📅 Crescimento mensal (%)  

---

## 🧠 Insights Gerados

A análise dos dados permitiu identificar:

- 📉 Períodos com prejuízo associados ao aumento de custos  
- 📊 Concentração de receita em poucos clientes  
- 📈 Variação da margem de lucro ao longo do tempo  
- 📅 Indícios de sazonalidade nos resultados financeiros  

---

## ⚙️ Tratamento e Preparação dos Dados

- Integração de múltiplas bases Excel  
- Padronização de colunas  
- Criação de tabela calendário  
- Modelagem relacional no Power BI  
- Tratamento de valores nulos e inconsistências  

---

## 🛠️ Tecnologias Utilizadas

- Power BI  
- Excel  
- DAX (Data Analysis Expressions)  

---

## 📂 Estrutura do Projeto

```bash
📦 powerbi-dashboard-financeiro
┣ 📂 Assets
┃ ┗ 📂 Backgrounds/
┃   ┣ EED-P00-DARK.png
┃   ┣ EED-P00-LIGHT.png
┃   ┣ EED-P01-DARK.png
┃   ┣ EED-P01-LIGHT.png
┃   ┣ EED-P02-DARK.png
┃   ┣ EED-P02-LIGHT.png
┃   ┗ TemaLight.json
┣ 📂 Data
┃ ┣ CadastroPlanoContas.xlsx
┃ ┣ Pagamentos.xlsx
┃ ┗ Recebimentos.xlsx
┣ 📂 Pbix
┃ ┗ dashboard_financeiro.pbix
┣ 📂 Images
┃ ┣ Visao-Deral.png
┃ ┗ Detalhamento.png
┣ README.md
┣ data_dictionary.md
┗ .gitignore

---

## 📊 Fonte dos Dados

Os dados utilizados são provenientes de múltiplas bases em Excel, contendo informações financeiras como receitas, custos, despesas e clientes.

*Obs: Os dados são fictícios e utilizados apenas para fins de estudo e portfólio.*

---

## 📈 Possíveis Evoluções

- Integração com banco de dados (SQL, PostgreSQL, etc.)  
- Automatização de atualização de dados  
- Publicação no Power BI Service  
- Criação de pipeline ETL  
- Inclusão de metas e projeções  

---

## 👨‍💻 Autor

**Raphael Medeiros**  
📍 Rio de Janeiro | RJ
🔗 LinkedIn: [https://www.linkedin.com/in/raphael-s-medeiros/]

---

## ⭐ Sobre o Projeto

Este projeto foi desenvolvido como parte do meu portfólio em dados, com foco em Business Intelligence, análise de dados e construção de dashboards orientados a negócio.
