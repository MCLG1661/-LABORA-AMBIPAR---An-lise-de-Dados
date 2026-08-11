##  <img width="384" height="89" alt="Labora_Logo_Novo_1_Laranja@2x" src="https://github.com/user-attachments/assets/1c222bef-3d11-4812-b1a7-25b830186555" />

## 📊 OPERAÇÃO LABORA/AMBIPAR — DATA ANALYTICS COM STREAMLIT
![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-1.28%2B-FF4B4B?logo=streamlit&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2.0%2B-150458?logo=pandas&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-5.0%2B-3F4F75?logo=plotly&logoColor=white)
![OpenPyXL](https://img.shields.io/badge/OpenPyXL-3.1%2B-217346?logo=microsoft-excel&logoColor=white)

Aplicação interativa de ***Data Analytics*** desenvolvida com Python e Streamlit para análise, visualização e acompanhamento de indicadores da Operação Labora/Ambipar.
O projeto foi desenvolvido como desafio do curso de ***Streamlit***, integrante da trilha ***Avançado em Data Science com Python — Alura***, utilizando dados operacionais como base para a construção de um dashboard voltado à exploração de informações e acompanhamento de KPIs. A aplicação transforma dados estruturados em indicadores e visualizações interativas, facilitando a identificação de padrões, análise de desempenho e interpretação dos resultados operacionais.

## 🌐 Aplicação Online

**[Acesse o Dashboard da Operação Labora/Ambipar](https://operacao-labora-ambipar-7ue494brbdawvj7pd3qqic.streamlit.app/)**

## 🎯 Objetivo

Desenvolver uma aplicação de análise de dados capaz de transformar informações operacionais em uma visão gerencial simples e interativa.
O dashboard permite acompanhar métricas relacionadas à operação, comparar resultados entre postos e CNPJs e identificar os principais responsáveis pelo volume e valor das notas fiscais processadas.
O projeto demonstra a aplicação prática de ***Python, análise de dados e visualização de informações*** na construção de ferramentas orientadas à tomada de decisão.

## 📊 Indicadores monitorados

O dashboard consolida os principais KPIs da operação:

- Total de postos
- Total de CNPJs
- Quantidade de notas fiscais
- Valor total recolhido
- Distribuição dos resultados por posto
- Distribuição dos resultados por CNPJ

## 🎯 Funcionalidades :

**Visão Geral**
- Apresentação das principais métricas da operação em uma visão consolidada.

**Rankings Por Valor**
- Top 10 Postos por Valor Recolhido
- Top 10 CNPJs por Valor Recolhido
-   
**Rankings Por Volume**
- Top 10 Postos por Quantidade de Notas
- Top 10 CNPJs por Quantidade de Notas
- 
**Análises Detalhadas**
- Análise completa por Posto
- Análise completa por CNPJ
- Formatação automática dos CNPJs
- Exploração dos dados diretamente pela interface
- 
**Possibilidade de exportação dos resultados em formato CSV**
- Dados consolidados por Posto
- Dados consolidados por CNPJ

## 🛠️Tecnologias & Finalidade :

- Python : Desenvolvimento e processamento dos dados
- Streamlit : Construção da aplicação e interface interativa
- Pandas : Manipulação, tratamento e análise dos dados
- Plotly: Desenvolvimento das visualizações interativas
- OpenPyXL : Leitura e integração com arquivos Excel  

## 📋 Estrutura do projeto :

```
Operacao-Labora-Ambipar/
│
├── assets/
│   └── dashboard-preview.png
│
├── Dashboard.py
├── requirements.txt
├── PLANILHA.xlsx
└── README.md
```
- Dashboard.py : Aplicação principal responsável pelo processamento dos dados, cálculos, visualizações e interface Streamlit.
- requirements.txt : Dependências necessárias para execução da aplicação.
- PLANILHA.xlsx : Base utilizada pelo dashboard para processamento dos indicadores.
- README.md : Documentação técnica e funcional do projeto.

## 📁 Estrutura dos Dados

A aplicação utiliza uma base Excel contendo informações operacionais necessárias para geração dos indicadores.

Entre os principais campos utilizados estão:

- **Posto** : Identificação do posto
- **CNPJ Ambipar** : Identificação do CNPJ relacionado à operação
- **Notas por posto** : Quantidade de notas processadas
- **Valor total recolhido** : Valor financeiro consolidado

## 🔄 Fluxo da Aplicação


No GitHub, o resultado visual será:

```text
Base Excel
    ↓
Leitura dos dados
    ↓
Pandas / Tratamento
    ↓
Agregações e cálculo dos KPIs
    ↓
Visualizações com Plotly
    ↓
Dashboard Streamlit
    ↓
Análise e exportação dos resultados

```

## 📸 Dashboard

A interface foi desenvolvida com Streamlit para facilitar o acompanhamento dos principais indicadores da operação.
[![Dashboard Operação Labora/Ambipar](assets/dashboard-preview)](https://operacao-labora-ambipar-7ue494brbdawvj7pd3qqic.streamlit.app/)

**KPIs**

- Total de Postos
- Total de CNPJs
- Total de Notas Fiscais
- Valor Total Recolhido
 
**Visualizações**

- Top 10 Postos por Valor Recolhido
- Top 10 CNPJs por Valor Recolhido
- Top 10 Postos por Quantidade de Notas
- Top 10 CNPJs por Quantidade de Notas

**Análises**

- Visão detalhada por Posto
- Visão detalhada por CNPJ
- Exportação dos resultados para CSV

## 💡 Competências demonstradas

Este projeto explora conceitos e práticas relacionados a:

- Data Analytics
- Python aplicado à análise de dados
- Manipulação e tratamento de dados
- Construção e acompanhamento de KPIs
- Data Visualization
- Desenvolvimento de dashboards
- Streamlit
- Análise de dados operacionais
- Transformação de dados em informações gerenciais
- Data-Driven Decision Making

## 📚 Contexto Acadêmico

Projeto desenvolvido como desafio do curso de Streamlit, integrante da trilha Avançado em Data Science com Python — Alura.
A proposta foi aplicar conceitos de análise e visualização de dados na construção de uma aplicação interativa utilizando um contexto operacional como estudo de caso.

## 👤 Autor

**Marcus Guedes**

Marketing | Data Science | Inteligência Artificial | Gestão de Projetos

🔗 GitHub: [https://github.com/MCLG1661]

🔗 LinkedIn: [https://www.linkedin.com/in/marcusguedes/]



