# Python Data Repository

Repositório de notebooks Jupyter para estudos e práticas em Ciência de Dados, incluindo análise exploratória, estatística, machine learning, big data e web scraping.

## Sobre o Projeto

Este repositório contém uma coleção de notebooks desenvolvidos em Python para explorar diferentes técnicas e ferramentas de análise de dados. Os notebooks foram criados para execução no Google Colab.

## Principais Funcionalidades

- **Análise Exploratória de Dados**: Análise de dados de produção hospitalar do SUS (Sistema Único de Saúde) utilizando Pandas
- **Análises com Python**: Avaliação de dados socioeconômicos como IDHM (Índice de Desenvolvimento Humano Municipal) com visualizações gráficas
- **Estatística Básica**: Trabalhos práticos de análise descritiva de dados cadastrais
- **Big Data com PySpark**: Manipulação de dados em larga escala utilizando Apache Spark
- **Machine Learning Avançado**: Previsão de séries temporais com modelos ARIMA, Prophet e AutoARIMA
- **Machine Learning Topics**: Leitura e processamento de diferentes formatos de dados (CSV, Excel)
- **Web Scraping**: Extração de dados de vagas do LinkedIn utilizando BeautifulSoup
- **Tech Challenge**: Análise de dados de exportação de vinhos brasileiros com regressão linear

## Stack Tecnológica

- **Linguagem**: Python 3
- **Ambiente**: Google Colab / Jupyter Notebook
- **Bibliotecas de Dados**: 
  - pandas
  - numpy
- **Bibliotecas de Visualização**:
  - matplotlib
  - seaborn
  - plotly
- **Machine Learning**:
  - scikit-learn
  - statsmodels
  - statsforecast
  - prophet
- **Big Data**:
  - pyspark
  - findspark
- **Web Scraping**:
  - requests
  - beautifulsoup4

## Como Executar

1. Acesse os notebooks diretamente no Google Colab clicando no badge "Open in Colab" presente em cada arquivo
2. Ou clone o repositório localmente:
   ```bash
   git clone https://github.com/rodrigosilvacio/python-data-repository.git
   ```
3. Abra os arquivos `.ipynb` em um ambiente Jupyter Notebook ou JupyterLab

## Estrutura do Repositório

```
.
├── Análise_exploratória_de_dados.ipynb    # Análise de dados hospitalares do SUS
├── Análises_Python.ipynb                   # Análise de IDHM com visualizações
├── Big_Data_Fundamentals.ipynb             # Manipulação de dados com PySpark
├── EstatisticaBasica_Python_Aula01_Solucao_16_06_2025.ipynb  # Estatística descritiva
├── Machine Learning Avançado.ipynb         # Séries temporais e previsões
├── Machine_Learning_Topics.ipynb           # Leitura de dados CSV/Excel
├── Python_Web_Scraping.ipynb               # Extração de vagas do LinkedIn
├── Tech_Challenge_Python.ipynb             # Análise de exportação de vinhos
└── pandas-read.txt                         # Exemplo de leitura com pandas
```

## Requisitos

Os notebooks foram desenvolvidos para execução no Google Colab, que já possui a maioria das dependências instaladas. Para bibliotecas adicionais, os próprios notebooks contêm células com comandos de instalação (`!pip install`).

Principais bibliotecas utilizadas:
- pandas
- numpy
- matplotlib
- seaborn
- plotly
- scikit-learn
- statsmodels
- pyspark
- beautifulsoup4
- requests
