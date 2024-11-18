# ecommerce-uml
Esquema conceitual para um sistema de ecommerce

## Descrição do Projeto

Este projeto consiste no esquema conceitual para um sistema de venda de produtos. O objetivo é modelar as entidades e relacionamentos envolvidos na venda de produtos por uma plataforma online. As principais entidades são: Produto, Estoque, Cliente, Pedido e Fornecedor.

### Entidades e Relacionamentos

- **Produto**: Produtos vendidos na plataforma. Cada produto possui um fornecedor. Um ou mais produtos podem compor um pedido.
- **Estoque**: Quantidade de cada produto disponível para venda.
- **Cliente**: Clientes podem se cadastrar com CPF ou CNPJ. O endereço do cliente determina o valor do frete. Um cliente pode fazer mais de um pedido e tem um prazo de devolução.
- **Pedido**: Pedidos são criados por clientes e contêm informações de status, endereço e status de entrega. Um pedido pode possuir um ou mais produtos e pode ser cancelado.
- **Fornecedor**: Cada produto possui um fornecedor.

### Refinamentos do Modelo

- **Cliente PJ e PF**: Uma conta pode ser PJ ou PF, mas não pode ter as duas informações.
- **Pagamento**: Pode ter cadastradas mais de uma forma de pagamento.
- **Entrega**: Possui status e código de rastreio.
