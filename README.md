Repositório para os Diagramas do banco de dados, realizado para o postgreSQL.
Foram usados como base: 
- Entidade User no modelo de dados do sistema.
    Especifique campos obrigatórios: id, nome, email, senha (hash), perfil (dono, funcionário, cliente), data de criação, status, etc.
    Considere campos opcionais como telefone, foto de perfil, preferências.
- Entidade Order (Pedido) com todos os atributos necessários.
    Inclua: id, id do usuário (cliente), data/hora do pedido, status, valor total, taxa de entrega, endereço, método de pagamento, etc.
- Entidade Inventory (produto/quantidade)
    Campos: id, id do produto, quantidade disponível, quantidade mínima para alerta, última atualização.
- Entidade Review (pedido, usuário, nota, comentário)
    Campos: id, id do pedido, id do usuário, nota (1-5), comentário, data/hora.
- Entidade Promotion (regra, validade)
    Campos: id, nome, descrição, tipo de desconto (percentual/fixo), valor, produtos/categorias participantes, data início/fim, ativo/inativo.
