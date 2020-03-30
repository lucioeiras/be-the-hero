Rota: A direção que você quer ir no site (uma página dele, etc.)
Recurso: Uma 'seção' do site. O que fica após a '/' (Ex: www.etefmc.com.br/acesso-interno)

Métodos HTTP:
- GET: Busca uma informação no backend. Sempre retorna alguma coisa.
- POST: Cria uma informação no backend.
- PUT: Altera uma informação no backend.
- DELETE: Deleta uma informação no backend.

Parâmentros:
- Query Params: Parâmetros nomeados enviados na rota após o sinal ? (Filtros, paginação, etc)
- Route Params: Parâmetros para identificar recursos
- Request Body: Corpo da requisição, utilizado para criar ou alterar recursos.

Bancos de dados: 
- SQL: MySQL, SQLite, Microsoft SQL Server, Oracle, etc.
    * Driver: Usa a sintaxe padrão do SQL 
    * Query Builder: Usa a sintaxe do JavaScript 
- NoSQL: MongoDB, etc.