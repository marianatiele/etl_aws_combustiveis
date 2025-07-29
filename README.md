# ETL com AWS Glue e S3

**Projeto de ETL dos dados de combustíveis (Gasolina, Diesel e Etanol) disponibilizados pelo portal do Governo Federal.**

## Visão Geral

Este projeto realiza o processo de **Extração, Transformação e Carga (ETL)** utilizando **AWS Glue** e **Amazon S3**, tratando os dados de combustíveis para posterior análise e uso em pipelines de dados.

* **Fonte de dados**: Portal de Dados Abertos do Governo Federal
*  **Tipos de combustíveis**: Gasolina, Diesel e Etanol
*  **Serviços AWS utilizados**: S3, Glue e IAM.

## Pipeline de Dados

1. **Upload dos arquivos CSV brutos para o Amazon S3** (Camada *Bronze*)
2. **Tratamento dos dados com AWS Glue** (limpeza, conversões, padronizações)
3. **Gravação dos dados processados no S3** (Camada *Silver* e *Gold*)

## Fluxograma do Projeto na AWS

<img width="699" height="414" alt="image" src="https://github.com/user-attachments/assets/65f4c153-33a6-4508-833e-a4aff36b1341" />

## Estrutura da Camada Medallion

* **Bronze Layer**: Dados brutos extraídos diretamente do portal
* **Silver Layer**: Dados limpos e estruturados
* **Gold Layer**: Dados prontos para análise e visualização

##  Objetivos do Projeto

* Automatizar o processo de ingestão e transformação de dados
* Criar uma arquitetura escalável e baseada em nuvem
* Servir como base para dashboards, análises preditivas ou relatórios

## Tecnologias e Ferramentas

* AWS Glue (Jobs, Crawlers)
* Amazon S3 (Data Lake)
* IAM (Permissões e funções)
* Amazon RDS MySQL (Camada final, opcional)
* Python (scripts Glue opcionalmente personalizados)




