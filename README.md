# DP-203_Hands-on_Azure-Synapse-Link-for-SQL_lab15


This repository contains the **Azure SQL Database variant** of *Lab 15: Synapse Link – SQL* from the Microsoft *DP-203: Azure Data Engineer* training.  
The project demonstrates secure identity management, network security, SQL querying, and a comparison of Synapse SQL Pools.

---

## Objective

- Set up **Synapse Link** integration with **Azure SQL Database**.  
- Enable secure access using **Managed Identities** (system-assigned & user-assigned).  
- Configure **network security** with VNet service endpoints and IP-based firewall rules.  
- Apply **Azure SQL Database security features**: Transparent Data Encryption (TDE), Auditing, and Microsoft Defender.  
- Run queries on the **AdventureWorksLT database** via Azure SQL Query Editor.  
- Compare the performance of **Synapse SQL Pools** (Serverless vs Dedicated).  

---

##  Prerequisites

- An active **Azure subscription**.  
- **Azure SQL Database** deployed with the **AdventureWorksLT sample database**.  
- An **Azure Synapse Workspace**.  
- Permissions to create and assign **Managed Identities**.  
- Permissions to configure **network security and firewall rules**.  

---

##  Setup Steps

1. Create a **Resource Group**.  
2. Deploy an **Azure SQL Database** with the **AdventureWorksLT sample database**.  
3. Create **Managed Identities** (system-assigned & user-assigned) and assign them to the SQL Server.  
4. Configure **VNet service endpoints** and **IP-based firewall rules**.  
5. Enable **Transparent Data Encryption (TDE)**, **Auditing**, and **Microsoft Defender** on the SQL Database.  
6. Test queries in the **Azure SQL Query Editor** (e.g., `SELECT TOP 1000 * FROM SalesLT.Customer`).  
7. Configure **Synapse SQL Pools** (Serverless and Dedicated) and compare their performance.  

---

## Azure Services Used

- **Azure SQL Database**  
- **Azure Synapse Analytics** (Serverless & Dedicated SQL Pools)  
- **Managed Identity** (system-assigned & user-assigned)  
- **Azure Network Security** (VNet service endpoints, firewall rules)  
- **Azure SQL Security** (TDE, Auditing, Microsoft Defender)  

---

## Linkedin: https://www.linkedin.com/posts/activity-7320907054343196672-biZy?utm_source=share&utm_medium=member_desktop&rcm=ACoAADxS3FkBc2-iV15F1-kiJgx5uikEUXEwWdM

