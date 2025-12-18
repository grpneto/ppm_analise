# 📊 Pesquisa da Pecuária Municipal (PPM) — Análise de Dados

Este repositório contém uma **análise exploratória dos dados da Pesquisa da Pecuária Municipal (PPM)**, disponibilizados pelo **IBGE**. O objetivo é analisar a evolução dos rebanhos no Brasil ao longo do tempo, bem como sua distribuição geográfica por regiões, estados e municípios, utilizando **Python** e **Power BI**.


## 📌 Sobre a Pesquisa da Pecuária Municipal (PPM)

A **PPM** é uma pesquisa anual realizada pelo IBGE que reúne informações sobre:
- Efetivo dos rebanhos por espécie;
- Produção de produtos de origem animal;
- Dados consolidados por município, estado e região.

Esses dados são amplamente utilizados para análises econômicas, planejamento agropecuário e estudos estatísticos.


## 📂 Estrutura do Repositório

- **images/**  
  Pasta destinada ao armazenamento de imagens, gráficos e visualizações geradas durante a análise.

- **Python_PPM.ipynb**  
  Notebook em Python responsável pelo carregamento, tratamento e análise exploratória dos dados da Pesquisa da Pecuária Municipal (PPM).

- **Dashboard_PPM.pbix**  
  Arquivo do Power BI contendo um dashboard interativo para visualização e exploração dos dados analisados.

- **README.md**  
  Arquivo de documentação do projeto, com descrição, objetivos, estrutura e instruções de uso.

## 🐍 Análise de Dados com Python

O notebook **Python_PPM.ipynb** contempla as seguintes etapas:

- Importação e limpeza dos dados;
- Tratamento de valores ausentes e padronização;
- Análise exploratória dos dados (EDA);
- Agregações por ano, UF, município e tipo de rebanho;
- Geração de visualizações para identificação de tendências e padrões.

Principais bibliotecas utilizadas:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`

![Dashboard PPM](images/Gráfico%20Evolução%20Geral%20por%20Ano.png)

## 📊 Visualização no Power BI

O arquivo **Dashboard_PPM.pbix** apresenta um dashboard interativo que permite:

- Acompanhar a evolução temporal dos rebanhos;
- Comparar estados e municípios;
- Filtrar dados por tipo de rebanho e período;
- Apoiar análises comparativas e tomada de decisão.

![Dashboard PPM](images/Tela%20com%20filtro.png)

## 🗂️ Fonte dos Dados

- **IBGE – Pesquisa da Pecuária Municipal (PPM)**  
  Dados oficiais disponibilizados pelo Instituto Brasileiro de Geografia e Estatística (IBGE), contendo informações anuais sobre efetivos da pecuária nos municípios brasileiros.  
  🔗 [Base dos Dados – PPM](https://basedosdados.org/dataset/f7df4160-7a6f-4658-a287-3a73d412ed10?table=707b3dee-88a2-424d-a790-7216eb431c78)


## 🎯 Objetivo do Projeto

Este projeto tem como objetivo:

- Aplicar técnicas de **análise exploratória de dados (EDA)**;
- Trabalhar com **dados públicos oficiais**;
- Desenvolver **visualizações analíticas** para apoio à interpretação dos dados;
