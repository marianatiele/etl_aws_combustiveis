# Projeto de Engenharia de Dados 
Bem-vindo à documentação do meu projeto de engenharia de dados. Este projeto envolve a utilização da Amazon S3 para armazenamento de dados CSV,  processamento de dados com base na arquitetura de Medallion (Bronze, Silver, Gold) e visualização de informações no Power BI.

## Visão Geral

Neste projeto, seguimos um fluxo de dados estruturado em várias camadas para garantir a qualidade e a integridade dos dados antes de apresentá-los no Power BI. Abaixo está uma visão geral de cada componente envolvido no processo.

## Tecnologias Utilizadas

- S3
- RDS PostgreSQL
- Google Colab
- Microsoft Power BI

## Fluxo de Trabalho

1. **Upload dos arquivos CSV brutos para o Amazon S3** (Camada *Bronze*)
2. **Tratamento dos dados com Google Colab e armazenamento na S3** limpeza, conversões e padronizações (Camada *Silver*)
3. **Gravação dos dados processados no RDS PostgreSQL** (Camada *Gold*)

## Fluxo da Pipeline de dados



##  Objetivos do Projeto

* Automatizar o processo de ingestão e transformação de dados
* Criar uma arquitetura escalável e baseada em nuvem
* Servir como base para dashboards, ML, análises preditivas ou relatórios

## Painel 

<img width="845" height="480" alt="image" src="https://github.com/user-attachments/assets/78c139cf-bea1-48fd-92eb-af4ed55a47ab" />

<img width="827" height="474" alt="image" src="https://github.com/user-attachments/assets/3dc3bc2e-2583-4445-9cbc-1aaaca9512b5" />

<img width="844" height="456" alt="image" src="https://github.com/user-attachments/assets/6d184f52-4c62-4fc0-8aa4-e24228839ea8" />

