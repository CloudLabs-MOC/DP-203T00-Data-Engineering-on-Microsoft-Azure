## **Getting Started**

1. Once the environment is provisioned, a virtual machine and lab guide will get loaded into your browser. Use this virtual machine throughout the workshop to perform the lab.
   
   ![LabEnvironment](media/vmandguide-env3.png)
   
1. To get the lab environment details, you can select the Environment Details tab. Additionally, the credentials will also be sent to your email address provided during registration.

   ![LabEnvironment](media/envdetails-env3.png)

### Log-in to the Azure portal and verify the pre-deployed resources

1. In the LabVM, double click on the **Azure portal** shortcut on the desktop.

     ![LabEnvironment](media/azureshortcut.png) 
     
1. On **Sign in to Microsoft Azure** blade, you will see a login screen, in that enter the following email/username and then click on **Next**.  
   * **Azure Username/Email**:  <inject key="AzureAdUserEmail"></inject>
   * **Azure Password**:  <inject key="AzureAdUserPassword"></inject>
  
1. If you see the pop-up like below, click **Skip for now(14 days until this is required)**.

   ![LabEnvironmentpop-up](media/skip.png)

1. If you see the pop-up  **Stay Signed in?**, click **No**.

1. If you see the pop-up **You have free Azure Advisor recommendations!** , close the window to continue the lab. 

1. If a **Welcome to Microsoft Azure** popup window appears, click **Maybe Later** to skip the tour.

1. Now you can see the Azure Portal Dashboard, click on **Resource groups** from the Navigate panel to see the resource groups.
   
   ![lab1 rg](media/rg.png "lab1 resource group") 
     
1. Navigate to the **DP203** Resource group and verify whether you have all the below resources deployed successfully.
  
    ![lab1 rg](media/rg-lab3.png "lab3 resource group") 

   - Application insights
   - Azure Cosmos DB account
   - Two Storage accounts
   - Key vault
   - Synapse workspace
   - Apache spark pool
   - Dedicated SQL pool
 
1. **Tools included:** *PowerBI Desktop* which is required in Module 16 is already installed in the VM.

    **NOTE:** The notebook **Lab 2 - Explore with Spark.ipynb** required in **Exercise 1 Task 3, Step 2 of Module 5** is already downloaded in the C:\LabFiles folder of the provided lab VM.Please use the same notebook for the lab steps.
 
1. Please ensure to **pause** the SQLPool whenever the environment is not in use.

   ![pause sqlpool](media/sqlpause.png "pause sqlpool") 

1. Please ensure to **stop** the virtual machine from the **Resources** tab whenever the environment is not in use.

   ![stop vm rg](media/resourcestab-env3.png "stop vm") 
   
   **Environment Uptime** : Lab environments typically include Virtual Machines and SQL Pool. VMs and SQL Pool have uptime limits to keep the cloud costs under control.Lab Duration and uptime limits are defined based on the average required time to complete the labs along with some buffer. This Lab environment includes 18 Hours of SQL Pool and VM uptime limit. Once the uptime limit is reached, all resources will remain in stopped/pause resource.

1. Click on **Next** from the bottom right corner and follow the instructions to perform the lab.

## Modules Included

  In this hands-on lab you will be performing the below modules:

- **Module 4 - Run interactive queries using serverless SQL pools**  
- **Module 5 - Explore, transform, and load data into the Data Warehouse using Apache Spark**
- **Module 7 - Ingest and load data into the Data Warehouse**
- **Module 8 - Transform data with Azure Data Factory or Azure Synapse Pipelines**
- **Module 9 - Integrate data from notebooks with Azure Data Factory or Azure Synapse Pipelines**
- **Module 10 - Optimize query performance with dedicated SQL pools in Azure Synapse**
- **Module 11 - Analyze and optimize Data Warehouse storage**
- **Module 12 - Support Hybrid Transactional Analytical Processing (HTAP) with Azure Synapse Link**
- **Module 13 - End-to-end security with Azure Synapse Analytics**
- **Module 16 - Build reports using Power BI integration with Azure Synapse Analytics**
 
