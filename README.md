# partitioning-with-spark

Particionando dados utilizando o apache spark

# Sobre o projeto

 A aplicação é uma aplicação simples que utilizei usando o google collaborate, onde é importada uma base de dados([Churn.csv](/Churn.csv)) e efetuamos o particionamento

 A ideia do projeto é exemplificar como funciona o particionamento do Spark, utilizando o pyspark


# Explicando conceitos


 ## Spark

 O Apache Spark é uma poderosa plataforma de processamento distribuído para big data, que permite realizar cálculos rápidos em grandes volumes de dados utilizando memória em vez de disco. Ele suporta múltiplos módulos, como SQL, machine learning e streaming, integrando facilmente com diversas fontes de dados.

 ## Pyspark

O PySpark é a interface do Apache Spark para a linguagem Python, que permite executar tarefas de processamento de dados em larga escala utilizando o ecossistema Spark. Ele oferece APIs para manipular dados em RDDs, DataFrames() e realizar operações avançadas como consultas SQL, machine learning e processamento de streams diretamente no Spark.


## Particionamento

O particionamento no Spark é o processo de dividir os dados em blocos menores, chamados de partições, que são distribuídos entre os nós do cluster para processamento paralelo. Isso melhora a eficiência, pois permite que o Spark processe os dados em várias máquinas simultaneamente.


## Como testar a aplicação?

Para testar a aplicação basta seguir em ordem de execução (de cima para baixo), os comandos dentro do módulo [partitioning](/partitioning.ipynb)

### Observação

Utilizei o Google Collaborate para postar o projeto do github para facilitar o teste. 



