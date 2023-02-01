# Desafio Nginx Node

Esse desafio envolve a utilização do nginx como proxy reverso. A idéia principal é que quando um usuário acesse o nginx, o mesmo fará uma chamada em nossa aplicação node.js. Essa aplicação por sua vez adicionará um registro em nosso banco de dados mysql, cadastrando um nome na tabela people.

O retorno da aplicação node.js para o nginx deverá ser:

Full Cycle Rocks!

- Lista de nomes cadastrada no banco de dados.

### Execute o Desafio:

docker-compose up --build

### Verifique o resultado acessando:

http://localhost:8080
