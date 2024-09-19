## API para integração com pedidos de venda.
### Descrição
A api foi solicitada em prol de atingir mais venda para a empresa e uma maior conectividade com clientes. Ela será utilizada para que o usuário envie um link ao cliente
onde o cliente escolherá oque ele deseja comprar (estará integrado com o banco de dados principal "firebird" para puxar os produtos), após isso enviará o pedido que 
chegará no sistema como um novo pedido de venda que informará que foi feito online.
### Requisitos

O sistema deve interagir com o banco de dados firebird diretamente.
O sistema deve identificar um cliente já cadastrado.
Sempre ao entrar no sistema o cliente deve inserir seus dados de cadastro.
  Deve ser solicitado pela api os dados obrigatórios da tabela fcfo("Nome Fantasia", "CPF", "Número de telefone", "Endereço")
  (Sempre lembrando que qualquer campo que seja definido como obrigatório no cadastro do cliente deve ser definido também como obrigatório na api)
