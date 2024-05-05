# SQL-CRIANDO-SISTEMAS-DE-BANCO-DE-DADOS-
INTRODUÇÃO AO SQL SERVER 2016, CRIANDO UM BANCO DE DADOS, MANIPULANDO DADOS, CONSULTANDO DADOS

INTRODUÇÃO AO SQL SERVER 2016

1.	Banco de Dados Relacional
Um Banco de dados relacional é uma arquitetura na qual os dados são armazenados em tabelas retangulares, semelhantes a uma planilha. Na maioria das vezes, essas tabelas possuem uma informação chave que as relaciona.
Facilita a inserção, alteração, exclusão e recuperação de dados.

2.	Design do Banco de Dados
É fundamental para o seu desempenho, a construção de um banco de dados passa por quatro etapas: Modelo Descritivo, Conceitual, Lógico e Físico.
Descritivo: É um documento que indica a necessidade de construção de um Banco de Dados.
Conceitual: Extraímos informações do modelo descritivo (Substantivos e Propriedades)
Lógico: Esse modelo apresenta, em um formato de diagrama, as entidades e os atributos encontrados nos modelos anteriores.
Físico: Pode ser obtido por meio do diagrama lógico de dados e está associado ao software de gerenciamento de Banco de Dados, neste caso, o SQL Server 2016.
Tabelas(entidades): Local de armazenamentos das informações
Campos(atributos): Características da tabela
Chave Primária: Campo único que define a exclusividade da linha (Valores únicos, Não permite valores nulos, A tabela será ordenada pela chave primária (índice clusterizado) ).
Relacionamento: Relação entre tabelas através de um ou mais campos (1 para 1, 1 para N e M para N).
Dicionário de Dados: Complementa o diagrama físico descrevendo as características da tabela.

3.	Normalização de Dados
O processo de organizar dados e eliminar informações redundantes de um banco de dados é denominado normalização.(Criar tabela, definir relacionamentos de acordo com as regras denominada Formas Normais)

4.	Arquitetura Cliente Servidor

5.	As Linguagens SQL e T-SQL

6.	SQL Server

7.	Ferramentas de Gerenciamento

8.	SQL Server Management Studio (SSMS)

CRIANDO UM BANCO DE DADOS

1.	CREATE DATABASE: CREATE DATABASE <nome do banco de dados>
USE <nome do banco de dados>
2.	CREATE TABLE: 
CREATE TABLE TB_ALUNO
(COD_ALUNO 		INT,
NOME 			VARCHAR(50)
);
3.	Tipos de Dados: Inteiros, Bit, Numéricos exatos, Valores monetários, Números aproximados, Data e Hora, Strings de caracteres ANSI, Strings de caracteres Unicode, Strings Binárias, Outros tipos de Dados.
4.	Campo de autonumeração (IDENTITY): 
CREATE TABLE TB_ALUNO
(COD_ALUNO 		INT IDENTITY,
NOME 			VARCHAR(50)
);

5.	Constraints: (PRIMARY KEY, FOREING KEY, CHEK, UNIQUE, DEFAULT)

NULABILIDADE
CREATE TABLE TB_ALUNO
(COD_ALUNO 		INT	 IDENTITY 	NOT NULL,
NOME 			VARCHAR(50)	NOT NULL
);

MANIPULANDO DADOS

1.	Constantes
2.	Nserção de Dados
3.	Utilização de TOP em uma instrução INSERT
4.	OUTPUT
5.	Atualização e Exclusão de Dados
6.	Update
7.	Delete
8.	OUTPUT para DELETE e UPDATE
9.	Transações

CONSULTANDO DADOS

1.	SELECT
2.	Ordenação de Dados
3.	Operadores Relacionais
4.	Operadores Lógicos
5.	Consulta de Intervalos com BETWEEN
6.	Consulta com Base em Caracteres
7.	Consulta de Valores Pertencentes ou não a uma Lista de Elementos
8.	Lidando com Valores Nulos
9.	Substituição de Valores Nulos
10.	UNION
11.	EXCEPT e INTERSECT
