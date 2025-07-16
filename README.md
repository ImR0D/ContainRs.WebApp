# Pré-requisitos:
- [Dotnet 8.0](https://dotnet.microsoft.com/en-us/download/dotnet/8.0)


# Banco de Dados
- Para atualizar o banco de dados é necessário, na pasta do app, abrir o terminal e inserir o seguinte comando:
  - `Add-Migration InitialCreate`
  - Caso o comando execute devidamente, deverá exibir a mensagem: `Build succedded`
    
- Em seguida dar o update no migration para atualizar o banco de dados, através do comando:
    - `Update-Database`
  - *Caso bem sucedido, deverá ser criado um banco de dados local para a aplicação inicial*
   
- Inicializando o projeto
  - Na pasta do projeto é possível executá-lo diretamente, através do comando:
    - `dotnet run`
  - Ou executá-lo, também, através do Visual Studio por meio do comando
    - `Ctrl + F5`


# Arquitetura Inicial
- O projeto inicial desenvolvido e disponibilizado foi feito totalmente na arquitetura MVC


# Objetivo
- O objetivo principal é modificar o padrão arquitetural MVC e para o padrão de Arquitetura Limpa (Clean Architecture)
