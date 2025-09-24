# Análise de Dados Climáticos com Polars

![Python](https://img.shields.io/badge/Python-Linguagem%20de%20programação-3776AB?style=flat-square&logo=python)
![Polars](https://img.shields.io/badge/Polars-Processamento%20de%20dados-00BFFF?style=flat-square&logo=python)
![CSV](https://img.shields.io/badge/CSV-Formatos%20de%20dados-FF9900?style=flat-square&logo=google%20sheets)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-FF6600?style=flat-square&logo=jupyter)
![Data Analysis](https://img.shields.io/badge/Data%20Analysis-Exploração%20de%20dados-4CAF50?style=flat-square&logo=tableau)

## Descrição
Este repositório reúne notebooks voltados para a análise de dados climáticos do Brasil, utilizando a biblioteca **Polars**.  
O foco é explorar séries temporais meteorológicas, identificar padrões e realizar comparações entre diferentes estações e regiões.  

As análises incluem variáveis como:  
- Temperatura máxima e mínima  
- Precipitação acumulada  
- Umidade relativa do ar  
- Radiação solar  
- Velocidade e direção do vento  

O objetivo é oferecer uma visão ampla sobre o comportamento climático em diferentes estados, possibilitando:  
- Estudos de impacto ambiental  
- Compreensão de padrões sazonais  
- Apoio à formulação de políticas públicas  

Além disso, o repositório demonstra como lidar com grandes volumes de dados de forma eficiente utilizando **Polars**, garantindo rapidez na leitura, filtragem e agregação de informações.

## Funcionalidades
1. Leitura de arquivos CSV contendo dados meteorológicos.  
2. Conversão de tipos de dados e parse de datas e horas.  
3. Filtragem de dados por estado, cidade, estação ou intervalo de datas.  
4. Ordenação e limpeza de dados, incluindo tratamento de valores nulos.  
5. Agrupamento por mês, período do dia ou estação.  
6. Cálculo de médias, máximos e mínimos de variáveis meteorológicas.  
7. Pivot de tabelas para análise comparativa entre diferentes estações.  
8. Exportação de resultados processados em arquivos CSV.  
9. Análises exploratórias de séries temporais e tendências climáticas.  
10. Identificação de padrões extremos de temperatura e precipitação.  
11. Visualização resumida da variação de variáveis meteorológicas ao longo do tempo.  
12. Criação de tabelas médias por períodos específicos (ex.: B-R-O BRÓ no Piauí).  
13. Comparação de condições climáticas entre diferentes cidades e altitudes.  
14. Análise de variação de temperatura por períodos do dia (manhã, tarde, noite).  
15. Preparação de dados para possíveis visualizações gráficas ou dashboards.  

## Estrutura do Projeto
- **Aula_1**  
  Introdução à leitura e manipulação de dados climáticos com Polars.  
  Configuração do ambiente e importação de bibliotecas necessárias.  

- **Aula_2**  
  Exploração inicial dos dados meteorológicos, identificação de valores nulos e limpeza de registros.  
  Ajustes em tipos de dados e preparação para análise.  

- **Aula_3**  
  Primeiras análises exploratórias de séries temporais.  
  Observação de padrões sazonais e extremos climáticos.  
  Uso de funções de agregação para médias diárias e mensais.  

- **Aula_4**  
  Seleção e agrupamento de dados climáticos no Piauí: cidades de Teresina, Corrente e Piripiri.  
  Cálculo de médias de precipitação, umidade relativa, temperatura máxima e mínima.  
  Criação de tabelas resumo para o período B-R-O (setembro a dezembro).  

- **Aula_5**  
  Filtragem de estações meteorológicas do Amazonas.  
  Análise de temperaturas máximas e mínimas ao longo de um ano.  
  Pivot de dados para comparação entre diferentes estações.  
  Análise de variação de temperatura por período do dia na cidade de Manaus.  

- **Dados Exportados**  
  - CSVs com temperaturas máximas por estação e período  
  - CSVs com médias mensais de temperatura, precipitação e umidade  

- **Observações Finais**  
  O repositório demonstra como usar Polars para processar grandes conjuntos de dados meteorológicos de forma rápida e eficiente.  
  Permite expandir análises para outras regiões ou variáveis, mantendo a escalabilidade do processamento.  
