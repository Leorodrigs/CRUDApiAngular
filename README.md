# Projeto CRUD - Angular 10 + .NET 3.1

Este é um projeto CRUD (Create, Read, Update, Delete) desenvolvido utilizando Angular 10 para o frontend e .NET 3.1 para o backend. O projeto consiste em um sistema simples que permite realizar operações básicas de gerenciamento de dados.

## Requisitos

Antes de rodar o projeto, é necessário garantir que você tenha os seguintes pré-requisitos instalados:

- [Node.js](https://nodejs.org/en/) (compatível com as versoes 10 e 12)
- [Angular CLI](https://angular.io/cli) (pode ser instalado com o comando `npm install -g @angular/cli`)
- [.NET Core SDK 3.1](https://dotnet.microsoft.com/download/dotnet/3.1)

## Estrutura do Projeto

- **Frontend (Angular 10)**: Esta parte do projeto é responsável pela interface do usuário, onde é possível interagir com o CRUD.
- **Backend (.NET 3.1)**: A parte do backend é responsável pela manipulação de dados, oferecendo uma API para o frontend interagir.

O backend e o frontend estão separados em duas pastas, e você deve executar ambos para que o projeto funcione corretamente.

## Passos para Rodar o Projeto

### 1. Backend - .NET 3.1

1. Baixe o repositório `CRUDApiCSharp` do GitHub.
2. Navegue até a pasta do projeto backend no seu terminal ou prompt de comando.
3. Execute o comando para rodar o backend:
   dotnet run

### 2. Frontend - Angular 10

1. Navegue até a pasta do projeto Angular.
2. 2. Execute o seguinte comando para instalar as dependencias:
npm install
3. Execute o seguinte comando para iniciar o servidor de desenvolvimento:
ng serve

O frontend será iniciado e estará disponível em http://localhost:4200/pessoas

### Banco de Dados utilizado: SQLite
