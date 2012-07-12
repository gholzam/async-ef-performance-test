async-ef-performance-test
=========================

The project intends to show performance difference between asynchronous and synchronous data access models using Entity Framework.
Note that asynchronous functionality of EF is reached only for entities obtaining, entities updates is implemented using ADO.NET classes only.


Init setup
==========

1. The project requires .NET 4.5 framework and Visual Studio 11 (VS 11 Beta was used by me).
2. CrmEntitiesLarge.zip file contains test MS SQL Server 2012 database with ~10000 computers. Unzip it and attach the database to your SQL server instance. Fix files paths if needed.
3. Modify server's connection string in app.config to match your database instance.
4. Run Visual Studio under admin privileges.