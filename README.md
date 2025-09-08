# Data Quality e Insights Estratégicos com Databricks e PySpark

## 📌 Visão Geral
Este projeto é uma **Prova de Conceito (PoC)** desenvolvida como estudo prático no Databricks, utilizando **PySpark** para explorar, tratar e gerar insights a partir de dados de uma **loja virtual fictícia**.  
O foco foi **aumentar a qualidade dos dados** e estruturar informações que auxiliam na **tomada de decisão estratégica** do negócio.

---

## 🛠️ Tecnologias Utilizadas
- **Databricks Community Edition**
- **Apache Spark / PySpark**
- **Delta Lake**
- **DBFS (Databricks File System)**
- **Python 3**

---

## 📂 Estrutura dos Dados
O projeto utilizou 8 arquivos CSV representando o ecossistema de uma loja virtual:

- `categorias.csv` → categorias de produtos  
- `cidades.csv` → cidades de clientes e vendedores  
- `clientes.csv` → cadastro de clientes  
- `paises.csv` → países relacionados a clientes e vendedores  
- `produtos.csv` → informações de produtos  
- `vendedores.csv` → cadastro de vendedores  
- `vendas1.csv`, `vendas2.csv`, `vendas3.csv` → dados de vendas em diferentes períodos  

> ⚠️ Os arquivos CSV não estão inclusos neste repositório. A estrutura pode ser facilmente simulada em qualquer dataset de vendas para fins didáticos.

---

## 🧩 Estrutura do Projeto
databricks-pyspark-case/
│── notebooks/ # Notebooks com cada etapa do projeto
│ ├── 01_setup_dbfs.ipynb
│ ├── 02_ingestao_dados.ipynb
│ ├── 03_limpeza_transformacao.ipynb
│ ├── 04_modelagem_delta.ipynb
│ ├── 05_consultas_sql.ipynb
│ ├── 06_insights_negocio.ipynb
│ ├── 07_rotinas_manutencao.ipynb
│ ├── 08_dashboard_final.ipynb
│── README.md
│── requirements.txt # (opcional)
│── LICENSE # (opcional)




---

## 🎯 Funcionalidades
- Ingestão de arquivos CSV no **DBFS**.  
- Tratamento e padronização dos dados com **PySpark**.  
- Criação de tabelas otimizadas com **Delta Lake**.  
- Consultas exploratórias em **SQL e PySpark**.  
- Geração de insights estratégicos para o negócio.  
- Rotinas de manutenção e versionamento de dados.  

---

## 📊 Exemplos de Insights
- Identificação dos **produtos mais vendidos**.  
- Análise do **desempenho por vendedor e região**.  
- Mapeamento de clientes com maior potencial de receita.  
- Avaliação da **qualidade dos dados** (valores nulos, duplicados, inconsistências).  

---

## 🚀 Resultados
- Pipeline de ingestão e tratamento de dados configurado no Databricks.  
- Base de dados estruturada e otimizada em formato **Delta**.  
- Informações consolidadas para **suporte à decisão estratégica**.  
- Aprendizado prático em **Big Data com PySpark e Databricks**.  

---

## 📘 Aprendizados
- Estruturação de um ambiente **Data Lakehouse**.  
- Integração de dados heterogêneos em larga escala.  
- Boas práticas de manipulação de dados com PySpark.  
- Criação de rotinas de manutenção automatizadas.  

---

## 🔗 Documentação Completa
Para detalhes mais profundos (explicação de cada notebook e prints dos resultados), acesse:  
👉 [Documentação do Case no Notion](#) *(insira o link)*  

E confira também este case no meu portfólio online:  
👉 [Landing Page Profissional](#) *(insira o link)*  

---

## 📜 Licença
Este projeto foi desenvolvido para fins de estudo e portfólio. Licenciado sob [MIT](LICENSE).
