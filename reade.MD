clientes (id_cliente, nome, numero, data_nascimento)
 |
 |
/|\
vendas (id_venda, total_gasto, FK(id_cliente))
 |
 |
/|\
itens_venda (FK(id_venda), FK(id_cliente))
\|/
 |
 |
produto (id_produto, preco, descricao)
