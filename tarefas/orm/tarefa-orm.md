# Resumo ODBC
ODBC (Open Database Connectivity) é uma API padrão da indústria que permite que aplicativos acessem e manipulem dados em vários bancos de dados usando uma linguagem de consulta estruturada (SQL). Ele fornece uma camada de abstração entre o aplicativo e o banco de dados subjacente, permitindo que desenvolvedores escrevam código independente do banco de dados específico. Para utilizar o ODBC em Python, o primeiro passo é estabelecer uma conexão com o banco de dados usando `pyodbc.connect()`, fornecendo os detalhes de conexão necessários. Em seguida, você cria um cursor para executar consultas SQL e manipular os resultados conforme necessário. Após concluir as operações desejadas, é importante confirmar as alterações e, por fim, fechar tanto a conexão quanto o cursor para liberar recursos do sistema.

# Resumo ORM
ORM (Object-Relational Mapping) é uma técnica de programação que permite aos desenvolvedores manipular bancos de dados relacionais usando objetos de programação em vez de consultas SQL diretamente. Ele mapeia os objetos de uma aplicação para as tabelas de um banco de dados, automatizando a conversão entre dados armazenados em tabelas e objetos em código.

A biblioteca SQLAlchemy em Python é uma poderosa ferramenta ORM que simplifica significativamente a interação com bancos de dados relacionais. Com o SQLAlchemy, os desenvolvedores podem definir modelos de dados como classes Python e manipular o banco de dados por meio desses modelos. Essa biblioteca lida automaticamente com a tradução entre objetos Python e as instruções SQL necessárias para operar nos dados armazenados. 

Ao utilizar o ORM do SQLAlchemy, os desenvolvedores podem definir modelos de dados por meio de classes, mapeá-los para tabelas no banco de dados, executar consultas e manipular dados usando métodos e expressões SQLAlchemy, além de gerenciar transações de forma eficiente. Essa abordagem simplifica consideravelmente o desenvolvimento de aplicativos, aumenta a portabilidade do código e reduz a necessidade de escrever SQL manualmente.

# Scripts
- [ORM](script-orm.py)
- [ODBC](script-odbc.py)

