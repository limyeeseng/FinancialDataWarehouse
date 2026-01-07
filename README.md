# Overview

This repository is an example of ETL workflows built with SQL Server Integration Services (SSIS). The workflow moves data from Data Source to Destination:   

### 1. **Transactional database to Data Warehouse**
   - Workflow that read from "financial_transactions_db.dbo.financial_transactions" into "financial_data_warehouse.dbo.financial_transactions".
   - [Setup Database](https://github.com/limyeeseng/FinancialDataWarehouse/wiki/Setup-Database)
   - [Customer Financial Transactions workflow](https://github.com/limyeeseng/FinancialDataWarehouse/wiki/Customer-Financial-Transactions-workflow)
   
### 2. **Excel to Database table**
   - Workflow that read from Excel file containing exchange rates, transform datatypes and insert into "financial_data_warehouse.dbo.exchange_rates".
   - [Exchange rates worfklow](https://github.com/limyeeseng/FinancialDataWarehouse/wiki/Exchange-rates)
   
### 3. **Rest API to Flat file**
   - A comprehensive collection of YouTube video tutorials that will guide you through the ins and outs of the Microsoft BI Stack. Learn at your own pace with step-by-step instructions and in-depth discussions.
   - [YouTube README](Youtube/README.md)
   - [YouTube Video Links](Youtube/youtube-video-links.md)

## Key Technologies:
- Microsoft SQL Server and Integration Services.
- Visual Studio and SQL Server Integration Services Projects.
 
