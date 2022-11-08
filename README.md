## Projeto All-For-One

## O que devo desenvolver?

Hoje você fará um projeto com o codinome All For One em que praticará todos os conceitos de SQL já ensinados até aqui. Porém, você vai usar um banco de dados totalmente diferente, então dê tchau para o sakila e dê boas vindas ao Northwind, que será usado neste projeto. 

Neste projeto você terá os seguintes desafios:

- Desafios de SELECT e criação de dados;
- Desafios sobre filtragem de dados;
- Desafios de manipulação de tabelas.

#### Abrir essa Issue e o PR

- [x] Abrir Issue
- [x] Abrir o PR

## Revisão de conteúdo:

#### Material necessário:
- [x] [Dia 01: Banco de Dados SQL](https://app.betrybe.com/learn/course/5e938f69-6e32-43b3-9685-c936530fd326/module/94d0e996-1827-4fbc-bc24-c99fb592925b/section/fa69c314-da3c-46e0-bcdb-43297772a43e/day/89e3203d-18e4-4329-9c8d-a3f40f2e4248/lesson/695be3a1-74b5-4c1d-9381-b3655397a00f)
- [x] [Dia 02: Encontrando dados em um Banco de Dados](https://app.betrybe.com/learn/course/5e938f69-6e32-43b3-9685-c936530fd326/module/94d0e996-1827-4fbc-bc24-c99fb592925b/section/fa69c314-da3c-46e0-bcdb-43297772a43e/day/727eca61-054b-45c5-bf26-b7958c09ad6d/lesson/8d5829df-e74b-448f-b74a-05e1b8a16543)
- [x] [Dia 03: Filtrando dados de forma específica](https://app.betrybe.com/learn/course/5e938f69-6e32-43b3-9685-c936530fd326/module/94d0e996-1827-4fbc-bc24-c99fb592925b/section/fa69c314-da3c-46e0-bcdb-43297772a43e/day/0798d603-86d8-4b98-849e-06094bfa936c/lesson/16e08471-e5b4-440d-b0ef-2b79104f4573)
- [x] [Dia 04: Manipulando Tabelas](https://app.betrybe.com/learn/course/5e938f69-6e32-43b3-9685-c936530fd326/module/94d0e996-1827-4fbc-bc24-c99fb592925b/section/fa69c314-da3c-46e0-bcdb-43297772a43e/day/a66b200c-8dc8-4231-a33a-4262877856af/lesson/a9afd7c8-dc77-4670-982e-c4b28f64ee67)
- [x] [Mentoria Banco do Spotify](https://app.betrybe.com/learn/course/5e938f69-6e32-43b3-9685-c936530fd326/live-lectures/17907612-170d-4ac4-8332-db126bd1ef35/recording/7b016113-338d-47cf-954e-72ada80356ff)
- Dica: [Documentação oficial MySQL](https://dev.mysql.com/doc/refman/8.0/en/)
- Dica: [Lidando com datas no MySQL](https://popsql.com/learn-sql/mysql/how-to-query-date-and-time-in-mysql)
- Dica: [Documentação sobre restrições de chaves estrangeiras no MySQL](https://dev.mysql.com/doc/refman/5.7/en/create-table-foreign-keys.html)


#### Pré-Requisitos do Projeto:
- [x] Verificar conexão com seu Banco de Dados.
- [x] Efetuar a leitura das Informações importantes sobre o projeto, dicas, como queries que serão desenvolvidas.

## Requisitos obrigatórios do Projeto:

#### Requisitos iniciais:
- [x] 1 - Exiba apenas os nomes dos produtos na tabela _products_.
- [x] 2 - Exiba os dados de todas as colunas da tabela _products_.
- [x] 3 - Escreva uma query que exiba os valores da coluna que representa a _primary_ key da tabela **`products`**.
- [x] 4 - Conte quantos registros existem na coluna **`product_name`** da tabela **`products`**.
- [x] 5 - Monte uma query que exiba os dados da tabela **`products`** a partir do quarto registro até o décimo terceiro
- [x] 6 - Exiba os dados das colunas **`product_name`** e **`id`** da tabela **`products`** de maneira que os resultados estejam em ordem alfabética dos nomes.
- [x] 7 - Mostre apenas os **`ids`** dos 5 últimos registros da tabela products (a ordernação deve ser baseada na coluna **`id`**).
- [x] 8 - Faça uma consulta que retorne três colunas, respectivamente, com os nomes 'A', 'Trybe' e 'eh', e com valores referentes a soma de '5 + 6', a string 'de', a soma de '2 + 8'.

#### Desafios sobre filtragem de dados:
- [x] 9 - Mostre todos os valores de **`notes`** da tabela **`purchase_orders`** que não são nulos.
- [x] 10 - Mostre todos os dados da tabela **`purchase_orders`** em ordem decrescente, ordenados por **`created_by`** em que o **`created_by`** é maior ou igual a 3.
- [x] 11 - Exiba os dados da coluna notes da tabela **`purchase_orders`** em que seu valor de **`Purchase`** **`generated based`** on **`Order`** é maior ou igual a 30 e menor ou igual a 39.
- [x] 12 - Mostre as **`submitted_date`** de **`purchase_orders`** em que a **`submitted_date`** é do dia 26 de abril de 2006.
- [x] 13 - Mostre o **`supplier_id`** das **`purchase_orders`** em que o **`supplier_id`** seja 1 ou 3.
- [x] 14 - Mostre os resultados da coluna **`supplier_id`** da tabela **`purchase_orders`** em que o **`supplier_id`** seja maior ou igual a 1 e menor ou igual 3.
- [x] 15 - Mostre somente as horas (sem os minutos e os segundos) da coluna **submitted_date** de todos registros da tabela **purchase_orders**.
- [x] 16 - Exiba a **`submitted_date`** das **`purchase_orders`** que estão entre 2006-01-26 00:00:00 e 2006-03-31 23:59:59.
- [x] 17 - Mostre os registros das colunas id e **`supplier_id`** das **`purchase_orders`** em que os **`supplier_id`** sejam tanto 1, ou 3, ou 5, ou 7.
- [x] 18 - Mostre todos os registros de **`purchase_orders`** que tem o **`supplier_id`** igual a 3 e status_id igual a 2.
- [x] 19 - Mostre a quantidade de pedidos que foram feitos na tabela **`orders`** pelo **`employee_id`** igual a 5 ou 6, e que foram enviados através do método(coluna) **`shipper_id`** igual a 2.

#### Desafios de manipulação de tabelas:
- [x] 20 - Adicione à tabela **`order_details`** um registro com **`order_id`**: 69, **`product_id`**: 80, **`quantity`**: 15.0000, **`unit_price`**: 15.0000, **`discount`**: 0, **`status_id`**: 2, **`date_allocated`**: NULL, **`purchase_order_id`**: NULL e **`inventory_id`**: 129.
- [x] 21 - Adicione com um único **`INSERT`**, duas linhas à tabela **`order_details`** com os mesmos dados do requisito 20.
- [x] 22 - Atualize os dados de discount do **`order_details`** para 15.
