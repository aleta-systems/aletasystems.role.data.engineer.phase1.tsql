# Technical Evaluation - tSQL

|||
|-|-|
|Default Evaluation Document|[Technical-Evaluation](./Technical-Evaluation.md)|

The database you will be querying on is based on  Wide World Importers sample database and is documented below

- [Overview](https://docs.microsoft.com/en-us/sql/samples/wide-world-importers-what-is?view=sql-server-2017) of Wide World Importers
- Wide World Importers database [catalog](https://docs.microsoft.com/en-us/sql/samples/wide-world-importers-oltp-database-catalog?view=sql-server-2017)


## Requirements

You will need access to a machine (Windows/Mac/Linux) with the following installed.

- Git (_with a GitHub Account_)
- Docker Community Edition ([Download Page](https://hub.docker.com/search/?type=edition&offering=community))
    - [Windows](https://hub.docker.com/editions/community/docker-ce-desktop-windows)
    - [MacOS](https://hub.docker.com/editions/community/docker-ce-desktop-mac)
- Azure Data Studio ([download](https://docs.microsoft.com/en-us/sql/azure-data-studio/download?view=sql-server-2017))
- _Alternatively_ SQL Server Management Studio. ([download](https://docs.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-2017))



## How to guide

1. Start Docker Container ([doc](./How-To/00-Start-Docker-Container.md))
2. Open Technical Question 
    - in Azure DataStudio `*.ipynb` ([doc](./How-To/01-Connect-To-AzureDataStudio.md))
    - in SSMS & GitHub ([doc](./How-To/02-Use-SSMS-Instead.md))
