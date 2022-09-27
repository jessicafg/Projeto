# atividadecontinua2

Desenvolva um micro servico que armazene dados de um produto, com nome, preco e categoria do produto, armazene os dados em banco de dados.

Envie os prints dos dados armazenados e o link do github com arquivos html, python, Dockerfile e o docker-compose.yml

# criar o banco

docker image build -t python-web .

docker ps (Precisar pegar o ID do container)

docker exec -it (ID do container) /bin/bash

mysql -uroot -p

digitar a senha do banco de dados = admin;

create schema teste;

use teste;

CREATE TABLE tbl_produto( produto_id BIGINT NOT NULL AUTO_INCREMENT, produto_nome VARCHAR(45) NULL, produto_preco VARCHAR(45) NULL, produto_categoria VARCHAR(45) NULL, PRIMARY KEY (produto_id));

exit

exit