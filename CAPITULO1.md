# Introdução

> Apresenta uma contextualização sobre o Big Data,
> mostrando a importância e a necessidade de se
> trabalhar com grandes volumes de dados, e como
> isso pode ser benéfico para as empresas. O
> capítulo também aborda a evolução do Big Data,
> mostrando como ele se tornou uma ferramenta
> essencial para as empresas, e como ele pode
> ser utilizado para melhorar a eficiência e
> a eficácia dos processos de negócios.

## Understanding Big Data

Demostra através de exemplos(como: "2.5 quintillion bytes of data are
generated every day") que um grande volume de dados não estruturados(isto é,
dados que não estão organizados em um formato que possa ser facilmente
analisado) são gerados diariamente, e que esses dados podem ser utilizados
para melhorar a eficiência e a eficácia dos processos de negócios.

Além disso, destaca a difilculdade de se trabalhar com grandes volumes de
dados, apresentando tecnologias disponíveis para lidar com esses dados, como
o [Hadoop](https://hadoop.apache.org/): [HDSF](https://www.databricks.com/br/glossary/hadoop-distributed-file-system-hdfs)
e [MapReduce](https://www.devmedia.com.br/hadoop-mapreduce-introducao-a-big-data/30034).

## Evolution of Big Data

Expresa como o problema de visualização de grandes volumes de dados foi
registrado pela primeira vez em 1997 pela NASA [(Nesse relatório podemos ver
a quantidade de dados que a NASA estava gerando em 1997)](https://nssdc.gsfc.nasa.gov/nssdc/annual/1997/),
demostrando que o problema de lidar com grandes volumes de dados não é novo.
E que seu crescimento é exponencial, indo de 600 MB em 1950 de dados gerados
para em 2010 100 petabytes de dados gerados.

## Failure of Traditional Database in Handling Big Data

Mostra que os bancos de dados tradicionais não são capazes de lidar com
grandes volumes de dados, pois foram projetados para lidar com dados
estruturados, e não com dados não estruturados. Além disso, destaca que
devido ao grande volume de dados gerados diariamente, é necessário utilizar
hardware de ponta para armazenar e processar esses dados, gerando custos
elevados para as empresas. Isto combinado com falta de capacidade de
armazenar os dados na velocidade que são gerados, torna os bancos de dados
tradicionais[(RDBMS)](https://www.oracle.com/br/database/what-is-a-relational-database/)
inadequados para lidar com grandes volumes de dados.

|  **Attributes**   |       **RDBMS**        |           **Big Data**           |
| :---------------: | :--------------------: | :------------------------------: |
|  **Data volume**  | Gigabytes to terabytes |     Petabytes to zettabytes      |
| **Organization**  |      Centralized       |           Distributed            |
|   **Data type**   |       Structured       | Unstructured and semi-structured |
| **Hardware type** |     High-end model     |        Commodity hardware        |
|    **Updates**    | Read/write many times  |   Write once, read many times    |
|    **Schema**     |         Static         |             Dynamic              |

- **Data Mining**
  - Data mining é o processo de descobrir o conhecimento subjacente dos conjuntos de dados.
  - Trabalha com dados estruturados provenientes de planilhas, bancos de dados relacionais, etc.
  - É capaz de processar grandes conjuntos de dados, mas os custos de processamento são altos.
  - Pode processar conjuntos de dados que variam de gigabytes a terabytes.

- **Big Data**
  - Big data refere-se a grandes volumes de dados caracterizados por volume, velocidade e variedade.
  - Inclui dados estruturados, não estruturados ou semi-estruturados provenientes de bancos de dados não relacionais, como NoSQL.
  - Ferramentas e tecnologias de big data são capazes de armazenar e processar grandes volumes de dados a custos relativamente mais baixos.
  - É capaz de armazenar e processar dados que variam de petabytes a zettabytes.

> [Data Mining](https://cetax.com.br/data-mining/)

## 3Vs of Big Data

