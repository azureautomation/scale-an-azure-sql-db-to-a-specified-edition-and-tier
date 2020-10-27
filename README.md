Scale an Azure SQL DB to a specified edition and tier
=====================================================

            

This runbook scales an Azure SQL Database to the specified edition and tier. You can look up the available editions and tiers on [https://azure.microsoft.com/en-us/documentation/articles/sql-database-service-tiers/](https://azure.microsoft.com/en-us/documentation/articles/sql-database-service-tiers/).


It takes the following input parameters:


ResouceGroupName: The name of the resource group that the SQL server is part of.


ServerName: The SQL server name.


Database: The name of the database


DatabaseEdition: The edition that will be set for the database. It defaults to Basic if not set


PricingTier: The tier to be set if Standard or Premium is set for the edition. Basic does not have a pricing tier.


SubscriptionID: An optional subscription ID if you want to work against an Azure subscription. The default is subscription is selected if not set. 


![Image](https://github.com/azureautomation/scale-an-azure-sql-db-to-a-specified-edition-and-tier/raw/master/scalesqldb.png)


 

 

        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
