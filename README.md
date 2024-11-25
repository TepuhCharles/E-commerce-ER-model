# Modelando um cenário de E-Commerce usando o Enhanced Entity Relationship Diagrams!
# Entidades: Cliente, Produto, Pedido, Fornecedor, Estoque, Terceiro-vendedor
# Relacionamento
Produto(n) → Fornecedor(m);
Estoque(n) → Produto(m);
Cliente(1) → Pedido(m);
Vendedor terceiro(n) → Produto(m);
