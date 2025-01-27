# Aplicando diferentes engines no watsonx.data via watsonx.ai

## Objetivo

Este guia tem como objetivo fornecer uma visão geral de como usar diferentes Engines no watsonx.data de forma programática para realizar consultas usando notebooks no watsonx.ai.

## O que são engines no watsonx.data?

O watsonx.data é uma solução para armazenamento de dados na nuvem, como um lakehouse que permite aos usuários processar e analisar grandes conjuntos de dados de forma eficiente e escalável. Para alcançar isso, o watsonx.data utiliza uma variedade de engines que são projetados para lidar com diferentes tipos de dados e cargas de trabalho.

Os engines no watsonx.data são componentes de software que são responsáveis por processar e analisar os dados. Eles são projetados para lidar com diferentes tipos de dados, como dados estruturados, semi-estruturados e não estruturados, e podem ser utilizados para realizar uma variedade de tarefas, como consultas, agregações e processamento de dados em tempo real.


## Diferentes cenários, diferentes engines

Os diferentes engines são úteis em diferentes cenários, dependendo das necessidades específicas do projeto. Aqui estão algumas situações em que cada engine pode ser mais adequado:

### Spark
- Processos de ETL (Extração, Transformação e Carga).
- Inserção, transformação e preparação de dados para análises ou armazenamento em data lakes.
- Workloads de processamento intensivo, como agregações complexas e cálculos em larga escala.

Ideal para: Cargas de trabalho em batch, pipelines de dados e preparação para machine learning.

### Presto Java e C++
- Consultas transacionais para acesso rápido a dados.
- Business Intelligence (BI), como dashboards e relatórios interativos.
- Consultas ad-hoc em ambientes de análise distribuída.

Ideal para: Consultas SQL interativas e baixa latência em análises de dados estruturados ou semi-estruturados.

## O que existe nesse repositório:

Este repositório contém dois Notebooks que demonstram como usar a API do watsonx.data para realizar consulta, a partir de diferentes engines. O primeiro Notebook, chamado [Aplicando Spark engine no watsonx.data via watsonx.ai](https://github.com/laurapellizari/watsonx-data-engines-api/blob/main/%5BPT-BR%5D%20Aplicando%20%20Spark%20engine%20no%20watsonx.data%20via%20watsonx.ai%20.ipynb), demonstra como utilizar a API do watsonx.data para criar conexão, listar databases, realizar uma consulta e executá-la por meio do Spark. O segundo Notebook, [Aplicando diferentes engines no watsonx.data via watsonx.ai](https://github.com/laurapellizari/watsonx-data-engines-api/blob/main/%5BPT-BR%5D%20Aplicando%20diferentes%20engines%20no%20watsonx.data%20via%20watsonx.ai%20.ipynb), aplica o mesmo conceito, porém utilizando engines do Presto, como Presto Java e Presto C++.

## Requisitos

Para executar os códigos neste repositório, você precisará:

- Ter uma conta no IBM Cloud e ter acesso ao watsonx.data, com os bancos de dados e as engines configuradas.
- Ter acesso as credencias do Cloud Object Storage onde os dados estejam armazenados.
- Ter um projeto criado no watsonx.ai.
- Ter uma API Key da IBM Cloud para autenticar na API.
- Adicionar os dois notebooks ao seu projeto:
    - [Aplicando Spark engine no watsonx.data via watsonx.ai](https://github.com/laurapellizari/watsonx-data-engines-api/blob/main/%5BPT-BR%5D%20Aplicando%20%20Spark%20engine%20no%20watsonx.data%20atrav%C3%A9s%20via%20watsonx.ai%20.ipynb)
    - [Aplicando diferentes engines no watsonx.data via watsonx.ai](https://github.com/laurapellizari/watsonx-data-engines-api/blob/main/%5BPT-BR%5D%20Aplicando%20diferentes%20engines%20no%20watsonx.data%20via%20watsonx.ai%20.ipynb)

