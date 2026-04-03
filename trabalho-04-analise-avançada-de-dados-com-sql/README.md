# 📊 Trabalho 04 — Análise Avançada de Dados Com SQL

Este trabalho faz parte da disciplina **Introdução à Visualização de Dados e SQL** e tem como objetivo integrar a **criação de dashboards no Google Looker Studio** com a **manipulação de dados por meio de consultas SQL**.

---

## 🎯 Objetivo da atividade

Desenvolver um relatório interativo com múltiplas páginas no **Google Looker Studio**, além de aplicar consultas SQL para extração, filtragem, ordenação e agregação de dados.

---

## 📊 Parte 1 — Visualização de Dados

Foi desenvolvido um dashboard dividido em múltiplas páginas, contendo:

### 🔹 Página 1
- Tabela com os dados da base
- Campos exibidos:
  - `data_aula`
  - `unidade`
  - `modalidade`
  - `professor`
  - `inscritos`
  - `presentes`

### 🔹 Página 2
- Indicadores (Scorecards):
  - Total de inscritos
  - Total de presentes
- Gráfico de barras:
  - Quantidade de presentes por modalidade

### 🔹 Página 3
- Gráfico de barras:
  - Presentes por unidade
- Gráfico de pizza:
  - Distribuição por modalidade
- Série temporal:
  - Evolução de presença ao longo do tempo
- Controles interativos:
  - Filtro por unidade
  - Filtro por modalidade
  - Controle de período

### 🔹 Página 4
- Página final com:
  - Indicadores
  - Gráficos
  - Controles interativos
- Layout organizado para melhor visualização e análise
- Relatório configurado para compartilhamento


---

## 🧠 Parte 2 — Consultas SQL

Foram desenvolvidas consultas SQL aplicando diferentes conceitos:

### 🔹 Consultas básicas
- Seleção de dados com `SELECT`
- Filtragem com `WHERE`

### 🔹 Condições e operadores
- Uso de operadores:
  - `AND`, `OR`, `IN`
- Filtros combinados e condicionais

### 🔹 Ordenação de dados
- Uso de `ORDER BY` (crescente e decrescente)

### 🔹 Agrupamento e agregação
- `GROUP BY`
- Funções de agregação:
  - `COUNT()`
  - `AVG()`
  - `MIN()`
  - `MAX()`
  - `SUM()`

### 🔹 Filtros em grupos
- Uso de `HAVING` para filtragem de dados agregados

---

## 📁 Contexto das consultas

As consultas foram aplicadas em diferentes cenários, incluindo:

- Catálogo de filmes
- Base de funcionários
- Base de produtos

Permitindo a análise de:

- Disponibilidade de itens
- Desempenho e classificação
- Distribuição de dados por categorias
- Resumos estatísticos por grupo

---

## 🛠️ Ferramentas utilizadas

- Google Looker Studio  
- Google Sheets  
- SQL  

---

## 📄 Especificações

Os requisitos completos da atividade, bem como os scripts SQL e resultados esperados, estão descritos no **PDF fornecido pela disciplina**.

---

## 🚀 Considerações finais

Este trabalho consolida o uso da **análise avançada de dados com SQL**, permitindo transformar dados brutos em informações organizadas e úteis para análise.

A integração entre dashboards interativos e consultas estruturadas fortalece a capacidade de interpretação de dados e tomada de decisão.