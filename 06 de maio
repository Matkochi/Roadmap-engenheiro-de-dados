# Conceitos de Engenharia de Dados - Dia 06

## OLTP vs OLAP

**OLTP (Online Transaction Processing)**
- Foco em: Processamento de transações em tempo real
- Operações: INSERT, UPDATE, DELETE frequentes
- Modelo de dados: Normalizado (3ª Forma Normal)
- Exemplo: Sistemas de vendas, bancos

**OLAP (Online Analytical Processing)**
- Foco em: Análise de dados históricos
- Operações: Consultas complexas (SELECT)
- Modelo de dados: Desnormalizado (Star Schema, Snowflake)
- Exemplo: Data Warehouses, sistemas de BI

## ETL vs ELT

**ETL (Extract, Transform, Load)**
1. Extração dos dados
2. Transformação em staging area
3. Carga no destino
- Vantagem: Dados limpos no destino

**ELT (Extract, Load, Transform)**
1. Extração dos dados
2. Carga no destino (Data Lake)
3. Transformação quando necessário
- Vantagem: Mais flexível, adequado para dados não estruturados

## Data Lake vs Data Warehouse

**Data Lake**
- Armazena dados brutos em formato original
- Schema-on-read (esquema aplicado na leitura)
- Adequado para dados não estruturados
- Tecnologias: Hadoop, S3, Azure Data Lake

**Data Warehouse**
- Dados estruturados e modelados
- Schema-on-write (esquema definido antes)
- Otimizado para análise
- Tecnologias: Redshift, BigQuery, Snowflake
