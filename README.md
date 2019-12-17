# SQL-Server-Tutorial-3---How-to-Set-Buffer-Pool-Size-in-SQL-Server
SQL Server Tutorial 3 - How to Set Buffer Pool Size in SQL Server

Steps: ---
1. Open Sql Server Management Studio.
2. Connect SQL Server with credentials.
3. Create Folder for Buffer Pool (Folder Name - 'SQLSVRCACHE' in your location).
4. Run the below Query in Query Window
 
 USE master
 GO

5. Run below Query for buffer pool off.

 ALTER SERVER CONFIGURATION
     SET BUFFER POOL EXTENSION OFF;
 GO

6. Run below Query for Set Buffer Pool.

 ALTER SERVER CONFIGURATION
 SET BUFFER POOL EXTENSION ON
     (FILENAME = 'E:\SQLSVRCACHE\SQLSvr2014.BPE', SIZE = 10 GB);
 GO
 
 
 Video URL : https://chittranjanmahto.blogspot.com/2019/08/sql-server-tutorial-3-how-to-set-buffer.html
