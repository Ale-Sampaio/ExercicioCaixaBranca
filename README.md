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
![Planilha Teste Estatico](https://github.com/Ale-Sampaio/ExercicioCaixaBranca/assets/121987957/ed46f655-3766-49ad-96eb-dcefdfd26e1a)

