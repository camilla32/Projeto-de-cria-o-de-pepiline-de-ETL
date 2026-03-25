# 📊 Pipeline ETL de Dados de Compras (Python + Google Colab)

## 🚀 Sobre o Projeto

Este projeto consiste no desenvolvimento de um pipeline de ETL (Extract, Transform, Load) utilizando Python, com execução no Google Colab. O objetivo é simular um fluxo de dados de compras, desde a geração de dados sintéticos até sua transformação e armazenamento.

O pipeline foi projetado para ser simples, reprodutível e adaptável, permitindo a execução sem necessidade de arquivos externos.

---

## ⚙️ Tecnologias Utilizadas

* Python
* Pandas
* NumPy
* SQLAlchemy
* SQLite
* Google Colab

---

## 🔄 Etapas do Pipeline

### 1. Extract (Extração)

* Geração de dados sintéticos simulando pedidos de compras
* Criação de colunas como:

  * ID do pedido
  * Cliente
  * Valor
  * Categoria
  * Data do pedido

### 2. Transform (Transformação)

* Padronização dos nomes das colunas
* Conversão de tipos de dados
* Criação de novas variáveis:

  * Categoria de valor (Baixo, Médio, Alto)
  * Mês do pedido

### 3. Load (Carga)

* Exportação dos dados tratados para:

  * Arquivo CSV
  * Banco de dados SQLite

---


## ▶️ Como Executar

1. Acesse o Google Colab
2. Faça upload do notebook ou copie o código
3. Execute todas as células
4. Os arquivos serão gerados automaticamente:

   * dados_tratados.csv
   * etl_compras.db

---

## 📊 Possíveis Análises

* Faturamento total
* Ticket médio por cliente
* Distribuição de vendas por categoria
* Análise mensal de pedidos

---

## 💡 Diferenciais do Projeto

* Geração de dados sintéticos integrada
* Pipeline completo em um único script
* Integração com banco de dados
* Estrutura pronta para evolução

---

## 🚀 Possíveis Melhorias

* Integração com APIs externas
* Automatização do pipeline
* Criação de dashboards (Excel ou Power BI)
* Implementação de logs e monitoramento

---

## 👩‍💻 Autora

Projeto desenvolvido por Camila Silva para fins de estudo e portfólio na área de dados.

---

## 📌 Observação

Este projeto utiliza dados sintéticos, sendo ideal para demonstração de habilidades em engenharia e análise de dados.
