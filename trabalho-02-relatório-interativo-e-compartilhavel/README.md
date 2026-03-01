# 📊 Trabalho 02 — Consolidação do Contador (Relatório Interativo e Compartilhável)

Este trabalho faz parte da disciplina **Introdução à Visualização de Dados e SQL** e tem como objetivo a criação de um **relatório interativo e compartilhável no Google Looker Studio**, com foco na análise de transações bancárias.

---

## 🎯 Objetivo da atividade

Desenvolver um relatório estruturado e interativo capaz de apresentar informações detalhadas sobre diferentes **transferências bancárias**, permitindo análise de saldo, movimentações e comportamento financeiro ao longo do tempo.

---

## 📁 Fontes de dados utilizadas

Para a construção do relatório, foram utilizadas duas fontes de dados:

- Arquivo **CSV**
- **Google Sheets** (planilha vinculada)

Os dados foram tratados previamente no Google Sheets para garantir:

- Correção de tipos de campos (Texto, Número, Data)
- Padronização de nomenclaturas
- Conversão correta para valores monetários
- Correção de formatação de datas

---

## 🛠️ Tratamento de dados realizado

Antes da visualização final, foram aplicados ajustes importantes:

- Renomeação de colunas:
  - `Description` → `Type`
  - `Memo` → `Description`
  - `Temp 1` → `Frequency`
- Correção da coluna `Date` com criação de campo calculado (`New Date`)
- Padronização de texto (letras maiúsculas na coluna Type)
- Remoção do símbolo `$` nas colunas `Transaction Amount` e `Balance` para permitir conversão para tipo numérico
- Reaplicação do formato de moeda após tratamento

Essas etapas foram fundamentais para possibilitar o cálculo correto de métricas como média, máximo e mínimo.

---

## 📊 Visualizações desenvolvidas

O relatório contém:

- **Controle de período** (Jan 1, 2017 – Mar 31, 2017)
- Três gráficos do tipo **Scorecard**:
  - Average Balance (Saldo Médio)
  - Max Balance (Saldo Máximo)
  - Min Balance (Saldo Mínimo)
- **Gráfico de série temporal** exibindo a média do saldo ao longo do tempo
- **Tabela detalhada** com informações como:
  - Data
  - Tipo
  - Descrição
  - Valor da transação
  - Saldo atual

---

## 🧠 Contexto do exercício

O projeto **Consolidação do Contador** apresenta dados sobre transferências bancárias, incluindo:

- Número da transação
- Data
- Tipo
- Descrição
- Categoria
- Valor
- Saldo
- Frequência

O objetivo principal é permitir o **controle financeiro do período analisado**, identificando:

- Períodos com maior movimentação
- Maiores gastos
- Comportamento médio do saldo

---

## 🔗 Acesso ao relatório

O relatório pode ser acessado através do seguinte link:

👉 https://lookerstudio.google.com/reporting/865d6994-97a0-4d47-b05b-fdd87aab7965

---

## 🚀 Considerações finais

Este trabalho reforça a importância do **tratamento e preparação dos dados antes da análise**, demonstrando como ajustes simples podem impactar diretamente na qualidade das métricas e visualizações.

Além disso, consolida o uso de:

- Scorecards
- Séries temporais
- Tabelas detalhadas
- Controles interativos

O projeto contribui para o desenvolvimento da capacidade analítica e da construção de relatórios claros, organizados e orientados à tomada de decisão.