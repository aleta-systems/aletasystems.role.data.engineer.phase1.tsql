# How To use SSMS instead

This How-To will show you how to connect to the Docker container you just created with **SSMS**

## _default_ Credentials 

- **SQL Server Login**: `sa`
- **SQL Server Password**: `P@ssw0rd!` (or value of `SA_PASSWORD` in step 2 of [00-Start-Docker-Container](./01-Connect-To-AzureDataStudio.md))
- **SQL Server Port**: `14333`

![SSMS Connection](./assets/02-connect-ssms.png "Connect via SSMS")

## Viewing the ipynb file.

Github will natively renders `.ipynb` files, for example if you click [here](../Technical-Questions/10-AzureDataStudio-SQLNoteBook-Basic.ipynb) (_and wait_) you will see the rendered notebook.

1. Open the `.ipynb` on github 
2. Write the SQL Query and Save it in the format specified under `-- (SSMS) Save Filename as:`
