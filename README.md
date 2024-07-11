# Trabalho-de-Banco-de-Dados
https://vscode.dev/profile/github/c6abb244af12f8d0676c413c83b41800
https://community.cloud.databricks.com/?o=2496601924242997#notebook/1494557144959978/command/1494557144959979


Este trabalho (conforme link acima)  teve como objetivo o uso das lingagen PHYTON e SQL no DATABRIKS. O dataset utilizado foi o Bike Store Relational Database | SQL da plataforma KAGGLE, cuja descrição é a seguinte:

O banco de dados "Bike Store Relational Database" disponível no Kaggle é um exemplo de um banco de dados relacional que modela a operação de uma loja de bicicletas. Ele inclui tabelas que representam várias entidades e relacionamentos associados às vendas, produtos, clientes, funcionários e outras operações da loja. A seguir, uma descrição detalhada das principais tabelas e seus respectivos campos:

Descrição das Tabelas do Banco de Dados Bike Store
1. Products (Produtos)
product_id: Identificador único do produto.
product_name: Nome do produto.
brand_id: Identificador da marca.
category_id: Identificador da categoria do produto.
model_year: Ano do modelo.
list_price: Preço de tabela.
2. Brands (Marcas)
brand_id: Identificador único da marca.
brand_name: Nome da marca.
3. Categories (Categorias)
category_id: Identificador único da categoria.
category_name: Nome da categoria.
4. Stores (Lojas)
store_id: Identificador único da loja.
store_name: Nome da loja.
phone: Número de telefone da loja.
email: E-mail da loja.
street: Rua.
city: Cidade.
state: Estado.
zip_code: Código postal.
5. Customers (Clientes)
customer_id: Identificador único do cliente.
first_name: Primeiro nome do cliente.
last_name: Sobrenome do cliente.
phone: Número de telefone do cliente.
email: E-mail do cliente.
street: Rua.
city: Cidade.
state: Estado.
zip_code: Código postal.
6. Staffs (Funcionários)
staff_id: Identificador único do funcionário.
first_name: Primeiro nome do funcionário.
last_name: Sobrenome do funcionário.
email: E-mail do funcionário.
phone: Número de telefone do funcionário.
active: Indicador de atividade do funcionário.
store_id: Identificador da loja onde o funcionário trabalha.
manager_id: Identificador do gerente do funcionário.
7. Orders (Pedidos)
order_id: Identificador único do pedido.
customer_id: Identificador do cliente que fez o pedido.
order_status: Status do pedido.
order_date: Data do pedido.
required_date: Data requerida para entrega.
shipped_date: Data de envio do pedido.
store_id: Identificador da loja que recebeu o pedido.
staff_id: Identificador do funcionário que gerenciou o pedido.
8. Order Items (Itens do Pedido)
order_id: Identificador do pedido.
item_id: Identificador do item no pedido.
product_id: Identificador do produto.
quantity: Quantidade do produto no pedido.
list_price: Preço de tabela do produto.
discount: Desconto aplicado ao produto.
Relacionamentos
Products se relacionam com Brands e Categories através dos campos brand_id e category_id.
Orders se relacionam com Customers, Stores, e Staffs através dos campos customer_id, store_id e staff_id.
Order Items se relacionam com Orders e Products através dos campos order_id e product_id.
Staffs se relacionam com Stores através do campo store_id e também podem ter um gerente através do campo manager_id.
Propósito

Este banco de dados serve para ilustrar como uma loja de bicicletas pode gerenciar suas operações diárias, incluindo:

Cadastro de produtos, marcas e categorias.
Gerenciamento de lojas e funcionários.
Registro de clientes e seus pedidos.
Detalhamento de itens em cada pedido, incluindo quantidades e preços.

Esse modelo de dados é útil para análises de negócios, como análise de vendas, controle de estoque, desempenho de funcionários, e preferências dos clientes. É um excelente exemplo para praticar consultas SQL e operações de banco de dados relacionais.

Foram realizadas as seguintes atividades: criação do Banco de dados MVPSeabra,  criação de tabelas associadas ao Banco de Dados MVPSeabra, a verificação de todos os produtos comercializados e sua respectiva contagem, a quantidade de bike por ano do modelo produzido, a relação de clientes, os clientes por estado, a verificação de quais cidades tinham mais clientes,  as cidades com mais de dez clientes, clientes por estado, a relação e o número de lojas por estado, todos os pedidos realizados, a relação de funcionários, as marcas de bicicletas produzidas e as marcas disponíveis em cada loja.

Dificuldades e limitações: as dificuldades encontradas foram devidas a falta de experiência e prática no conteúdo da disciplina que é totalmente novo pra mim.

Autoavaliação: creio que com a aquisição de conhecimentos e experiência será possível a melhoria contínua na realização de análises como essa mas considero satisfatório pelo fato de poder utilizar várias ferramentas que, até então não as conhecia pois, para mim, o conteúdo do curso é novo por se tratar de uma mudança de carreira após mais de 30 anos como estatístico de uma organização federal.
