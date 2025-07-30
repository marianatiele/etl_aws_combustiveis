# Projeto de Engenharia de Dados 
Bem-vindo à documentação do meu projeto de engenharia de dados. Este projeto envolve a utilização da Amazon S3 para armazenamento de dados CSV,  processamento de dados com base na arquitetura de Medallion (Bronze, Silver, Gold) e visualização de informações no Power BI.

## Visão Geral

Neste projeto, seguimos um fluxo de dados estruturado em várias camadas para garantir a qualidade e a integridade dos dados antes de apresentá-los no Power BI. Abaixo está uma visão geral de cada componente envolvido no processo.

## Tecnologias Utilizadas

**Serviços AWS**: S3, RDS PostgreSQL

**Serviços GCP** Google Colab

**Visualização** Microsoft Power BI

## Fluxo de Trabalho

1. **Upload dos arquivos CSV brutos para o Amazon S3** (Camada *Bronze*)
2. **Tratamento dos dados com Google Colab e armazenamento na S3** limpeza, conversões e padronizações (Camada *Silver*)
3. **Gravação dos dados processados no RDS PostgreSQL** (Camada *Gold*)

## Fluxo da Pipeline de dados

<img width="771" height="350" alt="image" src="https://github.com/user-attachments/assets/f119d7d2-64fc-4317-bc8b-8ec1ff046b3b" />

##  Objetivos do Projeto

* Automatizar o processo de ingestão e transformação de dados
* Criar uma arquitetura escalável e baseada em nuvem
* Servir como base para dashboards, ML, análises preditivas ou relatórios




