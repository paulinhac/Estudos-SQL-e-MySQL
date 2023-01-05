CREATE DATABASE nome - criar um banco de dados

DROP DATABASE nome - apagar um banco de dados

SELECT * FROM nome_da_tabela - mostrar informações de uma tabela

CREATE TABLE table_name - criar tabela. As colunas da tabelas devem ser definidas entre parênteses, cada linha representando uma coluna, como no exemplo a seguir:

CREATE TABLE clientes                                                                                                                                                                                                     
(CPF VARCHAR(11),                                                                                                                                                                                                          
NOME VARCHAR (100),                                                                                                                                                                                                                                
ENDERECO VARCHAR (150),                                                                                                                                                    
IDADE SMALLINT,                                                                                                                                                             
SEXO VARCHAR (1),                                                                                                                                                          
LIMITE_CREDITO FLOAT,                                                                                                                                                                               
PRIMEIRA_COMPRA BIT(1));                                                                                                                                                                                                                                                                                                                                                                                                             

DROP TABLE nome_tabela - apagar tabela

ALTER TABLE nome_tabela ADD COLUMN (NOME_COLUNA TIPO_DE_DADO) - Add coluna

UPDATE nome_tabela SET NOME_COLUNA = 'novo dado'  WHERE CHAVE PRIMÁRIA = 'chave primária' - Atualizar um dado da tabela 

INSERT INTO nome_tabela( NOME_COLUNA, ...) VALUES ( 'dados', ...) - Inserir novas linhas na tabela!
