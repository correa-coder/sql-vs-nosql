# SQL vs NoSQL

Resumo das principais diferenças entre banco de dados SQL (**S**tructured **Q**uery **L**anguage) e NoSQL (**N**ot **o**nly **SQL**).

## Introdução

Os bancos de dados relacionais utilizam algebra relacional e teoria de conjuntos, além disso, utiliza-se esquemas estruturados em formato tabular com definição de colunas, que por consequência, há uma consistência maior na organização dos dados comparado ao NoSQL.

A abordagem NoSQL não foi criada para substituir os bancos relacionais, mas sim para suprir necessidades que não eram possíveis anteriormente, principalmente no cenário de BigData em que há um grande volume de dados e também na área de ciência de dados.

## Escalabilidade

Banco de dados relacionais escalam de forma vertical, ou seja, quanto maior o volume de dados, maior será o uso de recursos de hardware como processador, memória e armazenamento. Por outro lado, bancos NoSQL escalam de forma horizontal e a técnica mais utilizada neste contexto é a de particionamento de dados (sharding).

## Flexibilidade

Os bancos NoSQL se destacam por permitirem flexibiliade, mas gera a consequência de não ter uma linguagem específica para manipulação dos dados. Por outro lado, os bancos relacionais utilizam uma estrutura rígida e utiliza a linguagem padronizada (SQL) para interagir com o banco de dados.

## Performance

NoSQL possui alta performance em muitas situações, porém se não houver um planejamento sobre como os dados serão armazenados, pode perder rendimento ao fazer consultas no banco de dados. Por outro lado, o modelo relacional é bastante eficaz na consulta de registros, porém perde performance caso o volume de dados for muito grande.

---

## Principais SGBDs

### Relacionais

- Oracle
- MySQL
- SQLServer
- PostgreSQL

### NoSQL

- MongoDB
- Redis
- Cassandra
- Neo4J

---

## Referência

- Módulo 2 e 3 do bootcamp _Database Experience_ disponibilizado pela [DIO](https://www.dio.me/ "Digital Innovation One")
