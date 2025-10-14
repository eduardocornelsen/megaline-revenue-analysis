# Strategic Revenue Analysis of Megaline's Mobile Plans

## 🗺️ Table of Contents / Índice

### 🇬🇧 English Version
* [**Strategic Revenue Analysis of Megaline's Mobile Plans**](#strategic-revenue-analysis-of-megalines-mobile-plans)
    * [Project Summary](#-project-summary)
    * [Key Findings & Business Insights](#-key-findings--business-insights)
    * [Technical Approach & Tools](#%EF%B8%8F-technical-approach--tools)
    * [Project Files](#-project-files)
      * [Note on Data Availability](#-note-on-data-availability)
    * [View the Project](#-view-the-project)
* [**➡️ Ir para a versão em Português-BR**](#análise-estratégica-de-receita-dos-planos-da-megaline-português---br)

---

### 🇧🇷 Versão em Português-BR
* [**Análise Estratégica de Receita dos Planos da Megaline (Português - BR)**](#análise-estratégica-de-receita-dos-planos-da-megaline-português---br)
    * [Resumo do Projeto](#-resumo-do-projeto)
    * [Principais Descobertas e Insights de Negócio](#-principais-descobertas-e-insights-de-negócio)
    * [Abordagem Técnica e Ferramentas](#%EF%B8%8F-technical-approach--tools)
    * [Arquivos do Projeto](#-arquivos-do-projeto)
        * [Nota sobre a Disponibilidade dos Dados](#-nota-sobre-a-disponibilidade-dos-dados)
    * [Veja o Projeto](#-veja-o-projeto)
* [**➡️ Go to English version**](#strategic-revenue-analysis-of-megalines-mobile-plans)

---
---

## 📋 Project Summary

This project presents a comprehensive analysis of customer data for **Megaline**, a telecom provider, to determine which of its two prepaid plans—**Surf** or **Ultimate**—is more profitable. The primary goal is to provide data-driven insights that can guide the company's future marketing budget allocation.

The analysis is based on a 2018 dataset covering the usage patterns of 500 clients, focusing on their call, text, and data consumption. The process involved data cleaning, feature engineering, exploratory data analysis, and statistical hypothesis testing to compare the revenue streams from both plans.

---

## 💡 Key Findings & Business Insights

* **Higher Average Revenue:** The **'Ultimate'** plan consistently generates a higher average revenue per user (ARPU).
* **Revenue Volatility:** The **'Surf'** plan's revenue is more unpredictable, primarily driven by customers who frequently exceed their plan limits and incur significant overage charges.
* **No Regional Impact:** Statistical tests showed no significant difference in revenue generated from users in the NY–NJ metropolitan area compared to those in other regions.
* **Actionable Recommendation:** To maximize revenue and ensure predictability, marketing efforts should focus on promoting the **'Ultimate'** plan to attract and retain high-value customers.

---

## 🛠️ Technical Approach & Tools

My analytical process followed these key steps:
* **Data Wrangling & Preprocessing:** Cleaned and transformed raw usage data using **Python**, **Pandas**, and **NumPy**.
* **Feature Engineering:** Created new variables, such as monthly revenue per user, by aggregating calls, messages, and data usage into a single, cohesive dataset.
* **Exploratory Data Analysis (EDA):** Generated visualizations with **Matplotlib** and **Seaborn** to uncover trends in user behavior and revenue distributions.
* **Statistical Testing:** Conducted formal hypothesis tests using the **SciPy** library to statistically validate the differences in revenue between the plans.

The entire analysis is documented in a **Jupyter Notebook**.

---

## 📂 Project Files

* `megaline_plan_analysis_portfolio_FINAL_clean.ipynb`: The complete Jupyter Notebook containing all steps, from data loading and cleaning to analysis, visualization, and statistical conclusions.
* `README.md`: This summary file.

### 📝 Note on Data Availability

The dataset for this analysis was provided by the TripleTen platform and is proprietary. Therefore, the code in the notebook cannot be run locally without access to the original data files. However, all outputs, tables, and visualizations have been preserved within the notebook for a complete review of the methodology and results.

---
## 🚀 View the Project

**[View the Code on GitHub](YOUR_GITHUB_LINK_HERE)**

**[Open in Google Collab](SEU_LINK_DO_GITHUB_AQUI)**


---
---

# Análise Estratégica de Receita dos Planos da Megaline (Português - BR)

[Go to English version](#strategic-revenue-analysis-of-megalines-mobile-plans)

## 📋 Resumo do Projeto

Este projeto apresenta uma análise completa dos dados de clientes da **Megaline**, uma operadora de telecomunicações, para determinar qual de seus dois planos pré-pagos — **Surf** ou **Ultimate** — é mais lucrativo. O objetivo principal é fornecer insights baseados em dados que possam orientar a alocação do orçamento de marketing da empresa.

A análise foi baseada em um conjunto de dados de 2018 que cobre os padrões de uso de 500 clientes, com foco no consumo de chamadas, mensagens e internet. O processo incluiu limpeza de dados, engenharia de features, análise exploratória e testes de hipóteses estatísticas para comparar as fontes de receita de ambos os planos.

---

## 💡 Principais Descobertas e Insights de Negócio

* **Receita Média Superior:** O plano **'Ultimate'** gera consistentemente uma maior receita média por usuário (ARPU).
* **Volatilidade da Receita:** A receita do plano **'Surf'** é mais imprevisível, impulsionada principalmente por clientes que frequentemente excedem os limites do plano e incorrem em cobranças de excedentes significativas.
* **Sem Impacto Regional:** Os testes estatísticos não mostraram diferença significativa na receita gerada por usuários da área metropolitana de NY–NJ em comparação com os de outras regiões.
* **Recomendação Prática:** Para maximizar a receita e garantir previsibilidade, os esforços de marketing devem se concentrar na promoção do plano **'Ultimate'** para atrair e reter clientes de alto valor.

---

## 🛠️ Abordagem Técnica e Ferramentas

Meu processo analítico seguiu estas etapas principais:
* **Tratamento e Pré-processamento de Dados:** Limpeza e transformação dos dados brutos de uso utilizando **Python**, **Pandas** e **NumPy**.
* **Engenharia de Features:** Criação de novas variáveis, como a receita mensal por usuário, agregando dados de chamadas, mensagens e internet em um único dataset coeso.
* **Análise Exploratória de Dados (AED):** Geração de visualizações com **Matplotlib** e **Seaborn** para descobrir tendências no comportamento do usuário e na distribuição de receita.
* **Testes Estatísticos:** Condução de testes de hipóteses formais com a biblioteca **SciPy** para validar estatisticamente as diferenças de receita entre os planos.

Toda a análise está documentada em um **Jupyter Notebook**.

---

## 📂 Arquivos do Projeto

* `megaline_plan_analysis_portfolio_FINAL_clean.ipynb`: O Jupyter Notebook completo, contendo todas as etapas, desde o carregamento e limpeza dos dados até a análise, visualização e conclusões estatísticas.
* `README.md`: Este arquivo de resumo.

---

<div class='info'>

### 📝 Nota sobre a Disponibilidade dos Dados

O conjunto de dados para esta análise foi fornecido pela plataforma TripleTen e é proprietário. Portanto, o código no notebook não pode ser executado localmente sem acesso aos arquivos de dados originais. No entanto, todos os resultados, tabelas e visualizações foram preservados no notebook para uma revisão completa da metodologia e dos resultados.

---

## 🚀 Veja o Projeto

**[Abra o Notebook no Collab](SEU_LINK_DO_GITHUB_AQUI)**

**[Veja o Código no GitHub](SEU_LINK_DO_GITHUB_AQUI)**

