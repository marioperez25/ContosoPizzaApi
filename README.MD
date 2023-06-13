## About

Created with dotnet ``new webapi -f net6.0``

## Packages:

``dotnet add package Microsoft.EntityFrameworkCore.Sqlite --version 6.0``

``dotnet add package Microsoft.EntityFrameworkCore.Design --version 6.0``

``dotnet tool install --global dotnet-ef``

## Installation

Run ``dotnet tool install --global dotnet-ef``

## DB Migrations

1. Run dotnet ef migrations add **<MIGRATION_NAME>**
2. Run dotnet ef database update
