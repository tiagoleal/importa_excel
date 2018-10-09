# Importação de Planilha do Excel em Banco de dados Mysql
 Este script desenvolvido e homologado em ```python3.5 e python3.6``` realiza a importação de dados de uma planilha do excel, para um banco de dados Mysql.
      Exemplo:
      Para uma matriz 3x3 temos um total de 9 casas. Neste caso os numeros de 1 a 9, de tal forma que a soma dos elementos de cada linha, coluna e diagonais é sempre 15.

## Instalação
Para realizarmos a importação dos dados devemos instalar duas bibliotecas do python.
Executar estas duas instalações:

```
pip3 install openpyxl
pip3 install PyMySQL
```

## Mysql
Para restaurar o arquivos com o banco de dados, podemo executar o seguinte comando:

```
mysql -p < banco-20181009-1645.sql
```

## Execução do script
```
python3.6 importa.py
```
