# Importação de planilha do excel em banco de dados Mysql
 Este script desenvolvido e homologado em ```python3.5 e python3.6``` e realiza a importação de dados de uma planilha do excel, para um banco de dados Mysql.
     
## Instalação
Para realizarmos a importação dos dados devemos instalar duas bibliotecas do python:

```
pip3 install openpyxl
pip3 install PyMySQL
```

## Mysql
Para restaurar o banco de dados, podemos executar o seguinte comando:

```
mysql -p < banco-20181009-1645.sql
```

## Execução do script
Para executarmos basta estar dentro da pasta base do projeto e executar o seguinte comando:
```
python3.6 importa.py
```
