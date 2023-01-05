<h5>Os dados de uma tabela podem ser filtrados utilizando o nome da coluna que queremos ver. As colunas virão na ordem em que forem colocadas no filtro, e podemos add também um limite de quantas linhas queremos ver. </h5> 
<br>
SELECT CPF, NOME FROM nome_tabela LIMIT 5;

SELECT NOME, MATRICULA FROM nome_tabela;
<br><br>

<h5>Podemos usar os operadores =, >, <, <=, >= e <> para filtrar informações. Nos casos de caracteres, eles filtrarão por ordem alfabética.</h5>

<br>
SELECT * FROM nome_tabela WHERE NOME = 'João';

SELECT * FROM nome_tabela WHERE IDADE > 21;

SELECT * FROM nome_tabela WHERE DATA_NASCIMENTO <= '1992-01-05';

SELECT * FROM nome_tabela WHERE YEAR(DATA_NASCIMENTO) = 1992;
<br><br>

 <h5>Também podemos usar operadores lógicos para formar filtros compostos.</h5>
<br>
SELECT * FROM nome_tabela WHERE NOME = 'João' OR NOME = 'MARIA';

SELECT * FROM nome_tabela WHERE NOME = 'João' AND IDADE > 21;
