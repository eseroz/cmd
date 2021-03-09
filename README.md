


################## Visual Studio ##################

 - Remove Line Breaks : ^(?([^\r\n])\s)*\r?$\r?\n
 
 
################## SQL Server ##################

- Insufficient memory to continue the execution : sqlcmd -s sunucu/instans adı -e -d database adı -i script yolu
- Diagram creation permission : use [MNDAPP] EXEC sp_changedbowner 'sa'
