🚀 Pipeline de Engenharia de Dados com Databricks

"Databricks" (https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white)
"Python" (https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
"Apache Spark" (https://img.shields.io/badge/Apache%20Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
"SQL" (https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

📌 Sobre o projeto

Projeto prático de Engenharia de Dados desenvolvido utilizando Databricks Free Edition, Python, PySpark, Spark SQL e Delta Lake.

O objetivo é construir um pipeline ETL para processamento e transformação de dados fictícios de vendas de uma empresa, aplicando a arquitetura Medallion (Bronze, Silver e Gold).

O projeto simula um ambiente de processamento de dados empresariais, desde a ingestão até a preparação das informações para análises e indicadores de negócio.

🎯 Objetivos

- Desenvolver um pipeline de Engenharia de Dados.
- Trabalhar com processamento distribuído utilizando Apache Spark.
- Aplicar transformações com PySpark e SQL.
- Implementar a arquitetura Medallion.
- Organizar dados para análises empresariais.
- Desenvolver conhecimentos em arquitetura Lakehouse.

🛠️ Tecnologias utilizadas

Tecnologia| Aplicação
Python| Linguagem de programação
Apache Spark| Processamento distribuído
PySpark| Transformação e processamento de dados
Spark SQL| Consultas e manipulação de dados
Delta Lake| Armazenamento e gerenciamento de tabelas
Databricks| Ambiente de desenvolvimento e processamento

🏗️ Arquitetura Medallion

O projeto utiliza a arquitetura Medallion, organizada em três camadas:

🥉 Bronze — Ingestão

Camada responsável pelo armazenamento inicial dos dados recebidos, preservando os dados originais para processamento nas etapas seguintes.

🥈 Silver — Tratamento

Camada responsável pela limpeza, padronização e transformação dos dados, buscando melhorar sua qualidade e consistência.

🥇 Gold — Análise

Camada responsável pela organização dos dados tratados para consultas analíticas e geração de indicadores empresariais.

📊 Dados utilizados

O projeto trabalha com quatro conjuntos de dados fictícios:

- Clientes
- Produtos
- Vendedores
- Vendas

Os dados são utilizados exclusivamente para fins educacionais.

📈 Indicadores de negócio

A camada Gold contempla informações destinadas à análise de:

- Faturamento por produto.
- Faturamento por vendedor.
- Faturamento por região.
- Quantidade de vendas.

Esses indicadores permitem explorar informações comerciais e apoiar análises de desempenho.

⚙️ Fluxo de processamento

O pipeline segue o seguinte fluxo:

1. Ingestão dos dados na camada Bronze.
2. Limpeza e transformação na camada Silver.
3. Organização dos dados analíticos na camada Gold.
4. Consultas utilizando Spark SQL.
5. Preparação das informações para análises empresariais.

🧠 Competências desenvolvidas

- Engenharia de Dados.
- Processamento distribuído.
- ETL (Extract, Transform, Load).
- Apache Spark e PySpark.
- SQL.
- Delta Lake.
- Arquitetura Medallion.
- Conceitos de Lakehouse.

👨‍💻 Autor

Samir Marcelo

Estudante de Engenharia de Dados, Ciência de Dados e Inteligência Artificial.

🔗 "GitHub" (https://github.com/samirmarcelors)

---

📚 Projeto desenvolvido para fins educacionais e evolução prática em Engenharia de Dados.