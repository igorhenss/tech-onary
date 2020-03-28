# Grupos de palavras

##### Banco de dados: [ Database, DCL, DDL, DML, DQL, FK, PK, SQL, TCL ]

##### Desenvolvimento: [ API, Interface ]

##### Web: [ HTTP, HTTPS ]

------



# TechCionário



## A

##### API - Application Programming Interface - Interface de Programação de Aplicações

> A sigla API significa *Application Programming Interface*, em português Interface de Programação de Aplicações. Consiste, basicamente, em uma aplicação que conecta dois diferentes pontos (como, por exemplo, um cliente front-end com um banco de dados).



## D

##### Database - Banco de Dados

> Um banco de dados é uma estrutura que armazena informações organizadas em tabelas, que são objetos com campos que definem a estrutura na qual a informação será armazenada.

##### DCL - Data Control Language - Linguagem de Controle de Dados

> A DCL consiste nos comandos SQL que lidam com permissões e privilégios do banco de dados.

> Os únicos dois comandos DCL são GRANT e REVOKE.

##### DDL - Data Definition Language - Linguagem de Definição de Dados

> A DDL consiste nos comandos SQL que lidam com os *schemas* do banco de dados, definindo a estrutura dos objetos.

> Os comandos DDL mais comuns são CREATE, ALTER and DROP.

##### DML - Data Manipulation Language - Linguagem de Manipulação de Dados

> A DML consiste nos comandos SQL que lidam com a manipulação dos dados presentes nas tabelas do banco de dados.

> Os principais comandos DML são INSERT, UPDATE e DELETE.

> Não há consenso absoluto quanto à existência dos comandos DQL. Dessa forma, boa parte da comunidade de desenvolvimento define o SELECT como um comando DML.

##### DQL - Data Query Language - Linguagem de Query de Dados

> A DQL consiste nos comandos SQL que lidam com a busca de dados do banco de dados.

> O único comando DQL é o SELECT.

> Não há consenso absoluto quanto à sua existência. Boa parte da comunidade de desenvolvimento define o SELECT como um comando DML.



## F

##### FK - Foreign Key - Chave Estrangeira

> Em bancos de dados relacionais, uma chave estrangeira consiste em uma coluna ou um grupo de colunas que fornece uma ligação entre duas tabelas, utilizando uma referência da chave primária de uma tabela em outra.



## H

##### HTTP - HyperText Transfer Protocol - Protocolo de Transferência de HiperTexto

> O Protocolo de Transferência de HiperTexto é um protocolo sem estado utilizado para transferir dados pela rede. Ser um protocolo sem estado significa que cada comando é executado independentemente, sem conhecimento algum sobre comandos prévios.

> O protocolo utiliza um sistema de requisição-resposta, onde uma requisição é feita e uma resposta é retornada, ambas possuindo cabeçalhos que contêm informações cruciais sobre o comando.

##### HTTPS - HyperText Transfer Protocol Secure - Protocolo Seguro de Transferência de Hipertexto

> O Protocolo Seguro de Transferência de Hipertexto, como o nome sugere, é uma estratégia de implementação de HTTP onde os dados são criptografados e, só então, transferidos por uma conexão segura.

> A criptografia é bidirecional, feita tanto no cliente quanto no servidor. O protocolo se certifica de que o cliente é o único que pode decodificar a informação chegando do servidor.



## I

##### Interface

> Um ponto onde dois objetos se encontram e interagem. O termo pode ser usado em múltiplos contextos, mas normalmente significa a mesma coisa (adaptada ao contexto em questão).



## P

##### PK - Primary Key - Chave Primária

> Em bancos de dados relacionais, uma chave primária, também chamada de ID (identificação), é um conjunto de uma ou mais colunas cujos valores combinados definem a identificação de cada linha, o que as torna sempre únicas (o valor de uma chave primária nunca aparecerá em múltiplas linhas). Dessa forma, apenas uma composição de chave primária é permitida por tabela.

> Quando uma chave primária é composta por uma única coluna, o valor dessa coluna sempre será único. Por exemplo: se o tipo da coluna do ID for numérico e o valor do ID da primeira linha for zero (0), não haverá nenhuma outra linha com o valor zero (0) como seu ID.

> Quando a chave primárya é composta, toda a combinação dos valores é que não pode ser repetida. Por exemplo: se existem duas colunas numéricas (A e B) compondo o ID da tabela e os valores do ID da primeira linha são zero (0) na coluna A e um (1) na coluna B, não haverão outras linhas com os mesmos valores como seu ID. Entretanto, pode haver uma outra linha com os valores um (1) na coluna A e zero (0) na coluna B, já que a combinação [0, 1] é diferente da combinação [1, 0].



## S

##### SQL - Structured Query Language - Linguagem de Query Estruturada

> A SQL é uma linguagem projetada para a manipulação de dados mantidos em bancos de dados relacionais.



## T

##### TCL - Transaction Control Language - Linguagem de Controle de Transação

> A TCL consiste nos comandos SQL que lidam com as mudanças feitas com comandos DML no banco de dados.

> Os principais comandos TCL são COMMIT, ROLLBACK e SAVEPOINT.