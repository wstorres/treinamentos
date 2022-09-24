
#### ARTIGO <!--Obrigatorio-->

<SUB>[DATABASE](#) | [SQL](#) |<br /></SUB>
<sub>Por:<strong> Wagner Torres</strong> | Data: 23/09/2022</sub>

<img style="border-radius: 65px;" alt="" width="30" height="30" class="avatar avatar-user width-full border color-bg-default" src="https://avatars.githubusercontent.com/u/44095306?v=4">[<img src = "https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white">](https://github.com/wstorres)
___________________________________________
<!--INICIO DO PROJETO-->


<h2 align="center">Linguagem SQL</h2>


### O que é Linguagem SQL
<br />

O SQL é uma linguagem padrão para manipulação de registros em bancos de dados relacionais. A sigla SQL vem dos termos em inglês “Structured Query Language”, que podem ser traduzidos para o português como “Linguagem de Consulta Estruturada”. 

Trata-se ainda de uma linguagem declarativa que apresenta sintaxe simples e fácil de ser aprendida até por pessoas iniciantes na área da programação.
Conheça os 5 subconjuntos da linguagem SQL
Subconjuntos da linguagem SQL
Subconjuntos da linguagem SQL e seus comandos

A linguagem SQL apresenta uma organização estrutural muito bem definida que divide seus comandos em 5 subconjuntos diferentes. Cada um desses conjuntos apresenta objetivos específicos que explicaremos a seguir. Observe!

- DML: linguagem de manipulação de dados

O DML (Data Manipulation Language) é o subconjunto do SQL que define os comandos usados para manipular os dados armazenados em um banco. Esse é um dos conjuntos mais utilizados, pois ele fornece operadores que nos permitem inserir, excluir e alterar os registros de uma tabela, por exemplo. Os comandos mais importantes desse subconjunto são: INSERT, DELETE e UPDATE.

- DQL: linguagem de consulta de dados

O DQL (Data Query Language) é o conjunto SQL que define o comando mais popular da linguagem, o SELECT. Esse comando é essencial para que possamos consultar os dados que armazenamos em nosso banco.

- DDL: linguagem de definição de dados

O DDL (Data Definition Language) é o subconjunto SQL que apresenta comandos usados para gerenciar as estruturas do banco de dados. Com ele, podemos criar, atualizar e remover objetos da base, como tabelas e índices. Os comandos definidos pelo DDL são: CREATE, DROP e ALTER.

- DCL: linguagem de controle de dados

O DCL (Data Control Language) é o subconjunto no qual encontramos comandos para controlar o acesso aos dados da nossa base. Utilizando esse conjunto, conseguimos estabelecer restrições e permissões para quem acessa o banco por meio dos comandos GRANT e REVOKE.

- DTL ou TCL: linguagem de transação de dados

O DTL (Data Transaction Language) — também conhecido como TCL (Transaction Control Language) — é o subconjunto SQL que define comandos que utilizamos quando é necessário gerenciar transações feitas no banco. Isso significa que eles permitem iniciar, confirmar e desfazer determinadas alterações. Os comandos estabelecidos pelo conjunto são COMMIT, BEGIN e ROLLBACK.

### Conheça os principais comandos, funções e operadores do SQL!

Agora que você já entendeu como os comandos SQL são divididos entre os 5 subconjuntos da linguagem, vamos nos aprofundar mais um pouquinho no assunto e mostrar para que serve cada um deles. Confira!

- SQL CREATE 

O comando CREATE, conforme seu nome indica, serve para criar o banco de dados e as tabelas que ele contém. A instrução usada para isso é bem simples:

        CREATE DATABASE empresa;


Com o nosso banco criado, podemos começar a criar as tabelas em que vamos armazenar os registros. Para isso, usamos o comando CREATE TABLE, observe:

Código para criar tabelas
É importante observar que, ao criar a tabela, também estamos especificando as colunas que ela vai conter, os tipos de dados que cada uma vai suportar e o comprimento máximo para os campos do tipo VARCHAR.

- SQL INSERT

O comando INSERT é usado para inserir novos registros em uma tabela do banco. Agora que nossa tabela “funcionarios” já foi criada, podemos usar uma estrutura básica dessa instrução para começar a popular o banco. Observe:

        INSERT INTO funcionarios (id, nome, cargo) VALUES (1, 'Fernando', 'Analista de Sistemas');


Nesse breve exemplo que mostramos, você deve reparar que “funcionarios” é o nome da tabela e “id”, “nome” e “cargo” são as colunas da tabela que estamos adicionando novos dados.

- SQL UPDATE

Já o comando UPDATE é utilizado para atualizar os registros que foram armazenados no banco. Essa declaração é usada junto com a cláusula WHERE, que especifica exatamente a linha da tabela que terá seus dados alterados.

No exemplo acima, adicionamos um novo registro na tabela “funcionarios”, mas agora queremos atualizar um dos dados que inserimos, mais precisamente o cargo que foi especificado. Para isso, usamos o comando:

        UPDATE funcionarios SET cargo = 'Analista de Sistemas e Aplicações' WHERE id = 1;


- SQL DELETE 

O comando DELETE, como você já deve imaginar, é usado para excluir dados de uma tabela. Assim como o anterior, ele também é usado junto com a cláusula WHERE. Nesse caso, vamos imaginar que não precisamos mais das informações que inserimos nos exemplos acima e queremos apagá-las da nossa tabela. Podemos fazer isso da seguinte forma:

        DELETE FROM funcionarios WHERE id = 1;


- SQL SELECT 

O comando SELECT permite definir critérios para realizar consultas aos registros que foram armazenados no banco de dados. Nesse caso, a forma mais simples de busca que podemos fazer é consultar todos os campos de uma tabela, dessa forma:

        SELECT id, nome, cargo FROM funcionarios;


Entretanto, existem diversas outras maneiras de realizar consultas e, utilizando os operadores corretos, podemos deixar nossas buscas mais refinadas. 

Para ficar mais evidente, imagine que você quer consultar o nome do funcionário com id = 15. Novamente, para especificar exatamente qual é o dado que queremos visualizar, utilizamos a cláusula WHERE, conforme mostramos no comando abaixo:

        SELECT nome FROM funcionarios WHERE id = 15;


Esses são os comandos basicos emais utilizados para banco de dados SQL, vale a pena consultar os comandos mais avançados para aumentar os comandos na linguagem.       