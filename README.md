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
```sql


create table funcionarios(
  id_funcionario int primary key,
  nome_funcionario varchar (30),
  sobrenome_funcionario varchar (50),
  salario_funcionario decimal (10,2)
  );
```

```sql
 alter table funcionarios  add Data_Nascimento date;
 ```

 ```sql
  create table  departamento(
)  
 id_departamento int primary key,
 nome_departamento varchar (50),
 );  
```

```sql
alter table funcionario   add idDepartamento int;
```

 ```sql  
create table  projetos(   
id_projetos int primary key
```

```sql
);
id_projeto int primary key,
nome_projeto varchar (50),
 );   
  ```


  ```sql
 create table Alocacoes(   
 id_alocacoes int primary key,
 id_funcionarios int,
 id_projetos int
 );  
```

```sql
 create table clientes(
 id_cliente int primary key;
 nome_cliente varchar (50),
 );

 ```

 ```sql
id_clinete int primary key,
nome_cliente varchar (50)
);   
 ```
 ```sql  
 alter table projetos add IDcliente int;  
 ```
 ```sql  
 create table endereco(
 id_endereco int primary key
 );
  ```
  ```sql 
 alter table   funcionarios add IDendereco int;
  ```
  ```sql 
  alter table clientes add Nomecliente to NomeEmpresa;
   ```
   ```sql
  create table pedidos(
  id_pedidos int primary key,
  data_pedido date
  );
   ```
   ```sql
  alter table pedidos add id_clientes int; 
  ```
  ```sql
  create table ItensPedido(
 id_itenspedido int primary key,
id_pedido varchar (20)
);
 ```
 ```sql  
create table estoque(
id_estoque int primary key,
quantidade int
);   
```
```sql
 alter table estoque add IDproduto int;  
```
```sql  
 create table  venda(
 id_venda int primary key,
 datavenda date
 );
  ```
  ```sql 
 alter table venda add IDcliente int;  
```











































































































