# 👨‍💻 Sobre
Projeto de engenharia de dados baseado em um bootcamp realizado pelo canal Stack no Youtube.

O projeto consiste em pegar dados de uma API e persistir em um banco de dados relacional, como o Postgres e estruturar, enviar para um datalake, utilizando conceitos do Deltalake,
subindo para o Amazon S3 os dados brutos tratando e disponibilizando os dados da camada final para os clientes internos.

</br>

# 📚 Bibliotecas

* Sqlalchemy
* Pandas
* Dotenv
* Requests

</br>

# 🤔 Como rodar

1. Primeiramente, será preciso visitar o site da API e criar uma conta para ter acesso aos dados através de uma chave e link da conexão
2. Pegar as credenciais e criar seu arquivo .env com as chaves KEY e URL
3. Necessário também criar uma conta na AWS para criar a conexão com o banco de dados Postgres e para criar os buckets no S3
