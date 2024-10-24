# README - Spark com PySpark

## Visão Geral

Este projeto utiliza PySpark para realizar uma análise de dados sobre preços de combustíveis em diferentes estados do Brasil. O objetivo é processar e analisar dados para obter insights sobre a variação de preços e suas diferenças entre estados e produtos, especificamente focando no Etanol e na Gasolina.

## Estrutura do Projeto

- **Linguagem**: Python, utilizado para a lógica de ETL (Extração, Transformação e Carga).
- **Ambiente**: Jupyter Notebook, que permite uma interação mais dinâmica com os dados.
- **Base de Dados**: O projeto extrai dados do governo relacionados a preços de combustíveis, incluindo Etanol e Gasolina.


## Tecnologias Utilizadas

- **PySpark**: Framework para processamento de dados em larga escala.
- **Jupyter Notebook**: Ambiente interativo para desenvolvimento de projetos em Python.
- **Docker**: Para facilitar a configuração e execução do ambiente.

## Configuração do Ambiente

Para garantir a consistência do ambiente, utilizamos o Docker para subir as imagens do Jupyter Notebook e do Spark.

### Instruções para Configuração

1. **Puxar a imagem do Docker**:

   ```bash
   docker pull jupyter/all-spark-notebook:latest
   
2. **Rodar o container**:

   ```bash
   docker run -p 8888:8888 jupyter/all-spark-notebook:latest
3. Abra um navegador e vá para http://localhost:8888. Você verá a interface do Jupyter, onde poderá criar ou abrir notebooks.



