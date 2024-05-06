# TesteCaixaBranca

## Descrição:
A classe Java denominada TesteCaixaBranca tem como objetivo a verificação de usuários em um banco de dados. Utilizando a tecnologia JDBC (Java Database Connectivity), estabelece conexão com um banco de dados MySQL.
## Tecnologias Utilizadas:
#### Java: Uma linguagem de programação amplamente empregada para desenvolvimento de aplicativos em diversas plataformas, devido à sua orientação a objetos.
#### MySQL: Um sistema de gerenciamento de banco de dados relacional de código aberto amplamente adotado.
#### DriverManager: Uma classe em JDBC que gerencia uma lista de drivers de banco de dados, responsável por carregar e selecionar o driver JDBC apropriado para a conexão com o banco de dados.
## Erros no Codígo:
#### 1- Carregamento Incorreto do Driver JDBC: O código utiliza "com.mysql.Driver.Manager" para carregar o driver JDBC. Deve ser substituído por "com.mysql.jdbc.Driver".
#### 2- Concatenação inadequada de strings SQL: faltam espaços entre as cláusulas SQL.
#### 3 -Gerenciamento inadequado de recursos: os recursos como Connection, Statement e ResultSet não estão sendo fechados corretamente após o uso.
#### 4- Tratamento vazio de exceções: as exceções capturadas não estão sendo tratadas ou registradas de forma adequada.
## Planilha de Teste Estático

## Grafo de Fluxo
![Grafo de Fluxo](https://github.com/Ale-Sampaio/TesteCaixaBranca/assets/121987957/b69c7d2c-a366-495c-bd23-87c69d47a794)

## Nodos identificados:
#### 1-Inicio
#### 2-Conectar DB
#### 3-Driver Manager
#### 4-Verificar Usuario
#### 5-Montar SQL Statement
#### 6-Executar Consulta
#### 7-Verificar Resultado
#### 8-Fim

## Cálculo da Complexidade Ciclomática
#### V(G) = complexidade ciclomática.
#### E = número de arestas no grafo.
#### N = número de nós no grafo.
#### P = número de componentes conexos (1 para um único grafo).
#### V(G)=E−N+2P
#### V(G)=8−8+2(1)=2

## Caminhos Possiveis
#### 1:
1-2-3-4-5-6-7-8
#### 2:
1-2-8
#### 3:
1-2-3-4-8
#### 4:
1-2-3-4-5-8
#### 5:
1-2-3-4-5-6-8
#### 6:
1-2-3-4-5-6-7-8
#### 7:
1-2-3-4-5-6-7-2-3-4-5-6-7-8
#### 8:
1-2-3-4-5-6-7-2-3-4-8
#### 9:
1-2-3-4-5-6-7-2-3-4-5-8
#### 10:
1-2-3-4-5-6-7-2-3-4-5-6-8
#### 11:
1-2-3-4-5-6-7-2-3-4-5-6-7-8







