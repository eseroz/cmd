


################## Visual Studio ##################

 - Remove Line Breaks : ^(?([^\r\n])\s)*\r?$\r?\n
 
 
################## SQL Server ##################

- Insufficient memory to continue the execution : sqlcmd -s sunucu/instans adı -e -d database adı -i script yolu
- Diagram creation permission : use [MNDAPP] EXEC sp_changedbowner 'sa'

- Authoization sqlserver User : ALTER AUTHORIZATION ON DATABASE::PANDA2021 TO [sa];

- Enable service broker : ALTER DATABASE PANDA2021 SET ENABLE_BROKER WITH NO_WAIT;

- View service broker status : SELECT is_broker_enabled FROM sys.databases WHERE name = 'PANDA2021';
- Execute Large Script : SQLCMD -d <database-name> -i filename.sql

- Enable Service Broker - ALTER DATABASE MNDAPPDB SET ENABLE_BROKER;
                        - ALTER DATABASE MNDAPPDB SET NEW_BROKER WITH ROLLBACK IMMEDIATE
- Check Service Broker - SELECT is_broker_enabled FROM sys.databases WHERE name = 'MNDAPPDB';

 
 
Entity to json : https://csharp2json.io <b>
Json to Sql Script : https://sqlizer.io
