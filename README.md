# Alura-store

Alura Challenge BI: Reporting solutions in finances on a PBI dashboard

# Case study
A tactical dashboard of a company's finance area was developed here, in which an overview page and a scenario analysis page are presented.

# Database
Our client provided 4 databases on the financial sector, in MySQL, which are:

receipts (In Portuguese: tabela notas fiscais), 

products (In Portuguese: tabela produtos)

sellers (In Portuguese: tabela vendedores)

order (In Portuguese: tabela pedidos)



# Data Handling


Adjustment of the values of currency.


# Data Analyses


Costs: 

Custos = SUM(Produtos[custos])

Expenditure: 

Despesa = SUM('Notas Fiscais'[imposto]) + SUM('Notas Fiscais'[frete])

Profit: 

Lucro = [Receita] - [Custos] - [Despesa]

Revenue: 

Receita = SUM('Notas Fiscais'[valor_venda])


# Dashboard

https://app.powerbi.com/view?r=eyJrIjoiOWMzNjQ5NGUtMGE2YS00OTRmLTg4NzAtNDA5ZmVmZDcyMWY0IiwidCI6ImY1YTgxMzY2LWVjOWQtNDdhZC05YThmLWI0MWFkZjRlOTRmOCIsImMiOjl9
