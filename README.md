# readme 
````
``Aula 25/09/2024
``Exercicio SQL
``LUCAS MATHEUS
````



```sql
 create table clientes(
 id_cliente int primary key,
 nome_cliente varchar (100),
 email_cliente varchar (150),
 data_nascimento date,
 telefone_cliente varchar (15)
 );
 ```


 ```sql
 create table faturas(
 id_fatura int primary key,
 data_criacao date,
 valor_fatura decimal (10,2)
  );
```



  ```sql
   create table produtos(
   id_produto int primary key,
   nome_produto varchar (100),
   preco_produto decimal (8,2)
   );
   ```