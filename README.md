---
page_type: sample
languages:
- java
products:
- azure
description: "Getting Started with Sql - Manage Sql Server Keys With Azure Key Vault Key - in Java"
urlFragment: sql-database-java-manage-sql-secrets-in-key-vault
---

# Getting Started with Sql - Manage Sql Server Keys With Azure Key Vault Key - in Java #


  Azure SQL sample for managing SQL secrets (Server Keys) using Azure Key Vault -
   - Create a SQL Server with "system assigned" managed service identity.
   - Create an Azure Key Vault with giving access to the SQL Server
   - Create, get, list and delete SQL Server Keys
   - Delete SQL Server
 

## Running this Sample ##

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-libraries-for-java/blob/master/AUTH.md).

    git clone https://github.com/Azure-Samples/sql-database-java-manage-sql-secrets-in-key-vault.git

    cd sql-database-java-manage-sql-secrets-in-key-vault

    mvn clean compile exec:java

## More information ##

[http://azure.com/java](http://azure.com/java)

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
