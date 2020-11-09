
AZ Fundamentals: Database Solutions
----
####  SQL Overview
SQL Objects:
- servers
- database
- tables
- fields (columns)
- Records (rows)
- stored procedures
- views
--- 
#### Azure SQL Database Deployment
Azure CLI:   

	az sql server create --name xxxx ...  
	az sql server firewall-rule create xxxx
		
Windows PowerShell:
	
	 New-AzSqlServer -xxx
	 New-AzSqlDatabase -xxx
	 New-AzSqlServerFirewallRule -xxx

--- 
#### SQL Server Migration Assessment

Microsoft Data Migration Assistant v4.2
			
----
#### Exercise
- Compare SQL and NoSQL database

	SQL: 
	- Relational
	- Structured schema
	- Microsoft SQL Server
	- MySQL
	- Oracle Database

	NoSQL:
	- Non-relational
	- Non-structured schema
	- CosmosDB
	- MongoDB

- Deploy Azure SQL Database
- Connect to Azure SQL Database from on-premises

	Use: Microsoft SQL Server Management Studio
- Deploy CosmosDB

