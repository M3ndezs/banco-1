banco.1

```sql 
use bdteste;
```
# Exercício 1

``` sql
create table clientes(
id_cliente int primary key,
nome_cliente varchar(100),
email_cliente varchar(150),
dataNascimento date,
telefone_cliente varchar(15)
);
```
# Exercício 2

```sql
create table produtos(
id_produto int primary key,
nome_produto varchar (100) not null unique,
preco_produto decimal(8.2)
);
```
# Exercício 3

```sql
create table faturas(
id_fatura int primary key,
data_criacao timestamp default current_timestamp,
valor_fatura decimal (10.2)
);
```
teste