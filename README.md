Este foi o segundo projeto do módulo de back-end da Trybe. Nele foram trabalhados os apresendizados de todos os conceitos de SQL.

Para acessar este projeto, clone o presente repositório, entre na pasta, e acesse o projeto por meio do docker, seguindo os passos abaixo:
(é preciso ter o docker-compose instalado na versão 1.29 ou superior)
 - git clone git@github.com:FernandaGrein/backend-Project-mysql-All-for-one.git
 - cd backend-Project-mysql-All-for-one
 - docker-compose up -d
 - docker exec -it all_for_one bash
 - npm install
 - code .
 - as informações para a criação do banco de dados está presente no arquivo northwind.sql

O presente projeto possui 27 requisitos, os quais era preciso montar querys para acessar as informações do banco de dados northwind.
 - Foi montada um query que mostrava o nome dos produtos.
 - Foi montada um query que mostrava todos os dados da tabela produtos.
 - Foi contado os registros da coluna product_name.
 - Foram exibidos os dados da tabela products do quarto registro até o décimo terceiro.
 - Foram exibidos dados das colunas product_name e id da tabela products em ordem alfabetica.
 - Foi exibido apenas os 5 últimos ids da tabela products
 - Foi realizado uma coluna genérica que retorna 3 colunas com os nomes 'A', 'Trybe' e 'eh'.
 - Foi montada uma query que exibe os valores de notes da tabela purchase_orders que não são nulos.
 - Foi montada uma query que exibe os dados da tabela purchase_orders em ordem decrescente, ordenados por created_by, sendo este  maior que 3 
 - Foi exibido os dados da coluna notes, que são maiores de 30 e menores de 39, da tabela purchase_orders.
 - Foi exibido as submitted_date de purchase_orders do dia 26 de abril de 2006.
 - Foi exibido supplier_id de purchase_orders que seja, ou 1 ou 3.
 - Foi exibido supplier_id que seja, ou maior/igual a 1 ou menor/igual a 3.
 - Foi exibido as horas da coluna submitted_date de todos os registros da tabeala.
 - Foi exibido as submitted_date que estão entre 2006-01-26 00:00:00 e 2006-03-31 23:59:59.
 - Foram exibidos os registros das colunas id e supplier_id, nos quais supplier_id sejam tanto 1, 3, 5, ou 7.
 - Foram exibidos os registros que que tem o supplier_id igual a 3 e status_id igual a 2.
 - Foram mostrados os pedidos que foram feitos na tabela orders pelo employee_id igual a 5 ou 6.
 - Foi adicionado à tabela order_details um registro, com os dados passados pela Trybe.
 - Na sequencia, foram adicionados mais 2 registros com um único insert e com os mesmos dados recebidos anteriormente.
 - Foram atualizados os dados de discount do order_details.
 - Foram atualizados os dados da coluna discount para 30, onde o valor na coluna unit_price era menor que 10.0000.
 - O discount foi atualizado para 45 nos casos em que unit_price era maior que 10.0000 e o id era um número entre 30 e 40.
 - Foram deletados todos os dados em que a unit_price era menor que 10.0000.
 - Depois, deletados todos os dados em que a unit_price era maior que 10.0000.
 - E por fim, deletados todos os dados da tabela order_details.
