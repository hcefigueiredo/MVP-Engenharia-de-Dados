# MVP-Engenharia-de-Dados
MVP Engenharia de Dados Hugo Figueiredo


Link da Base: https://www.kaggle.com/datasets/josephcheng123456/olympic-historical-dataset-from-olympediaorg?select=Olympic_Athlete_Event_Results.csv


Link do trabalho: https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/3179027449756647/1154706511091136/8805629024990819/latest.html


O objetivo deste trabalho é construir uma pipeline de dados completa usando a plataforma Databricks Community, desde a coleta e organização dos dados até a análise final, utilizando os conceitos de data lakes e processamento com Spark. O foco está nos dados históricos das Olimpíadas, com o intuito de responder perguntas sobre os atletas, países e esportes mais relevantes ao longo dos anos.

Para isso, foram utilizados dois arquivos do dataset público disponível no Kaggle:

Olympic_Athlete_Bio.csv

Olympic_Athlete_Event_Results.csv

A modelagem dos dados será feita utilizando o padrão de camadas:

Bronze: dados brutos, exatamente como foram coletados.
Silver: dados limpos, estruturados e organizados em tabelas com schema.
Gold: tabelas analíticas, com métricas e agregações que facilitam a análise.

As perguntas que orientam este trabalho são:

Quais são os países que mais ganharam medalhas olímpicas?
Quais foram os atletas que mais ganharam medalhas olímpicas em uma edição?
Quais são os países que mais tiveram atletas nas Olimpíadas?
Qual esporte teve mais atletas nesse peírodo ?
Qual a porcentagem de homens e mulheres no esporte com maior número de atletas?
A partir disso, será possível criar gráficos e responder às perguntas com base em dados confiáveis e bem processados.


Passo a Passo e cada etapa de avaliacao está descrita no codigo disponibilizado no Databriks e no para dowload aqui.
