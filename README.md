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
# Exercícios complementares

# 1.
```sql
create table funcionarios(
id int primary key,
nome_funcionario varchar (50),
sobrenome_funcionario varchar (150),
salario decimal (5.2)
);
```
# 2.
```sql
alter table funcionarios add dataNacimento date;
```

# 3.
```sql
create table departamento(
id_Depertamento int primary key,
nome_depertamento varchar (50)
);
```

# 4.
```sql
alter table funcionarios add IDDEpartamento int;
```

# 5.
```sql
create table projeto(
id_projeto int primary key,
nomeProjeto varchar (50)
);
```

# 7. 
```sql
alter table funcionarios rename column sobrenome_funcionario to apelido_funcionario;
```

# 8.
```sql
create table clientes(
id_cliente int primary key,
nomeCliente varchar (50)
);
```

# 9.
```sql
alter table projeto add IDCliente int;
```

# 10.
```sql
create table enderecos(
id_endereco int primary key,
rua varchar (50),
cidade varchar (100),
estado varchar (100),
CEP varchar (8)
);
```

# 11.
```sql
alter table funcionarios add IDEnderecos int;
```

# 12.
```sql
alter table clientes rename column nomeCliente to nomeEmpresa;
```

# 13.
```sql
create table pedidos(
id_pedidos int primary key,
dataPedidos date
);
```

# 14.
```sql
alter table pedidos add IDClientes int;
```

# 16.
```sql

```

# 17.
```sql

```

# 18.
```sql

```

# 19.
```sql

```

# 20.
```sql

```
