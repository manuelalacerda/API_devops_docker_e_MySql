# 🚀 Projeto DevOps com Docker e MySQL

Este é um projeto simples utilizando **Docker** para containerização e **MySQL** como banco de dados.

---

## 👩🏾‍🦱 Integrante

### Manuela de Lacerda Soares Rm 564887


## 📦 Tecnologias utilizadas

* Docker
* MySQL
* API (backend)

## ▶️ Como executar o projeto

1. Clone o repositório:

```bash
[git clone https://github.com/manuelalacerda/API_devops_docker_e_MySql.git]
cd <nome-do-projeto>
```

3. Verifique se os containers estão rodando:

```bash
docker ps
```

## 🌐 Endpoint da API

A API estará disponível em:

```
http://20.164.205.21:8080/usuarios
```

## 🌐 Acessando o banco de dados

```
docker exedocker exec -it mysql_vendas mysql -u root -p
```

```
root
```

```
USE vendas_db;
```

```
INSERT INTO usuario (nome, email) VALUES ('Manuela Soares', 'manu@fiap.com.br');
```

```
SELECT * FROM usuario;
```


## 🛠️ Banco de Dados

* Banco: MySQL
* Configurado via Docker

Feito para fins acadêmicos 🚀
