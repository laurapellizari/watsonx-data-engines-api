# Aplicando diferentes engines no watsonx.data através da API

## Objetivo

Este guia tem como objetivo fornecer uma visão geral de como usar diferentes Engines no Watsonx.data de forma programática para realizar consultas. Ao final deste guia, você entenderá como configurar as credenciais, conectar-se ao Watsonx.data, listar os bancos de dados e executar consultas usando a API através de diferentes engines, como Spark, Presto Java e Presto C++.

## O que são engines no Watsonx.data?

O Watsonx.data é uma solução para armazenamento de dados na nuvem, como um datalake que permite aos usuários processar e analisar grandes conjuntos de dados de forma eficiente e escalável. Para alcançar isso, o watsonx.data utiliza uma variedade de engines que são projetados para lidar com diferentes tipos de dados e cargas de trabalho.

Os engines no watsonx.data são componentes de software que são responsáveis por processar e analisar os dados. Eles são projetados para lidar com diferentes tipos de dados, como dados estruturados, semi-estruturados e não estruturados, e podem ser utilizados para realizar uma variedade de tarefas, como consultas, agregações e processamento de dados em tempo real.


## Diferentes cenários, diferentes engines

Os diferentes engines são úteis em diferentes cenários, dependendo das necessidades específicas do projeto. Aqui estão algumas situações em que cada engine pode ser mais adequado:

### Spark
- Processamento de grandes volumes de dados: O Spark é ideal para processar grandes volumes de dados, pois é capaz de lidar com conjuntos de dados muito grandes e complexos.
- Análise de dados em tempo real: O Spark é útil para análise de dados em tempo real, pois é capaz de processar dados em tempo real e fornecer resultados rapidamente.
- Machine learning e deep learning: O Spark é uma boa escolha para machine learning e deep learning, pois é capaz de lidar com grandes volumes de dados e fornecer resultados precisos.
- Integração com outros sistemas: O Spark é fácil de integrar com outros sistemas, como o Hadoop, o Kafka e o Cassandra.

### Presto Java e C++
- Consultas em tempo real: O Presto Java é ideal para consultas em tempo real, pois é capaz de processar consultas rapidamente e fornecer resultados em tempo real.
- Análise de dados em tabelas: O Presto Java é útil para análise de dados em tabelas, pois é capaz de lidar com grandes volumes de dados e fornecer resultados precisos.
- Integração com outros sistemas: O Presto Java é fácil de integrar com outros sistemas, como o Hadoop, o Kafka e o Cassandra.
- Desenvolvimento de aplicações: O Presto Java é uma boa escolha para desenvolvimento de aplicações, pois é capaz de fornecer uma API simples e fácil de usar.

Em resumo, cada engine tem suas próprias limitações que devem ser consideradas ao escolher o engine mais adequado para um projeto. É importante avaliar as necessidades específicas do projeto e escolher o engine que melhor se adapte a essas necessidades.

## O que existe nesse repositório:

Este repositório contém dois Notebooks que demonstram como usar a API do watsonx.data para realizar consulta, a partir de diferentes engines. O primeiro Notebook, chamado [Aplicando a Spark engine no watsonx.data através da API](https://github.com/laurapellizari/watsonx-data-engines-api/blob/main/%5BPT-BR%5D%20Aplicando%20a%20Spark%20engine%20no%20watsonx.data%20atrav%C3%A9s%20da%20API.ipynb), demonstra como utilizar a API do watsonx.data para criar conexão, listar databases, realizar uma consulta e executá-la por meio do Spark. O segundo Notebook, [Aplicando diferentes engines no watsonx.data através da API](https://github.com/laurapellizari/watsonx-data-engines-api/blob/main/%5BPT-BR%5D%20Aplicando%20diferentes%20engines%20no%20watsonx.data%20atrav%C3%A9s%20da%20API.ipynb), aplica o mesmo conceito, porém utilizando engines do Presto, como Presto Java e Presto C++.

## Requisitos

Para executar os códigos neste repositório, você precisará:

- Ter uma conta no IBM Cloud e ter acesso ao watsonx.data, com os bancos de dados e as engines configuradas.
- Ter acesso as credencias do Cloud Object Storage onde os dados estejam armazenados.

### Opcional

Você pode executar os notebooks diretamente do watsonx.ai. Para isso, você precisa:
- Ter um projeto criado no watsonx.ai.
- Adicionar os dois notebooks ao seu projeto:
    - [Aplicando a Spark engine no watsonx.data através da API](https://github.com/laurapellizari/watsonx-data-engines-api/blob/main/%5BPT-BR%5D%20Aplicando%20a%20Spark%20engine%20no%20watsonx.data%20atrav%C3%A9s%20da%20API.ipynb)
    - [Aplicando diferentes engines no watsonx.data através da API](https://github.com/laurapellizari/watsonx-data-engines-api/blob/main/%5BPT-BR%5D%20Aplicando%20diferentes%20engines%20no%20watsonx.data%20atrav%C3%A9s%20da%20API.ipynb)

