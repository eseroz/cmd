


################## Visual Studio ##################

 - Remove Line Breaks : ^(?([^\r\n])\s)*\r?$\r?\n
 
 
################## SQL Server ##################

- Insufficient memory to continue the execution : sqlcmd -s sunucu/instans adı -e -d database adı -i script yolu
- Diagram creation permission : use [MNDAPP] EXEC sp_changedbowner 'sa'

- Authoization sqlserver User : ALTER AUTHORIZATION ON DATABASE::PANDA2021 TO [sa];
- 
- Enable service broker : ALTER DATABASE PANDA2021 SET ENABLE_BROKER WITH NO_WAIT;
- 
- View service broker status : SELECT is_broker_enabled FROM sys.databases WHERE name = 'PANDA2021';
