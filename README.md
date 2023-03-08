<p align="center">
<img src="https://www.imagar.com/wp-content/uploads/2018/06/azure.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>How to Create a Storage Account in Azure </h1>
This guide will build upon the previous tutorial where you created an Azure Subscription and Resource Group. In this tutorial, you will learn how to create a Storage Account within your Resource Group. A Storage Account is a container that houses all of your Azure Storage data objects, such as blobs, files, queues, tables and disks. The Storage Account provides a unique namespace for your Azure Storage data that's accessible from anywhere in the world over HTTP or HTTPS. Data in your storage account is durable and highly available, secure, and massively scalable. You can think of Azure Storage Accounts like a Google Drive or Drop Box on steroids. In addition to creating a storage account, you will learn how to upload, edit and download a basic text file within your storage account. <br />

<h2>Prerequisites</h2>

- [Creating a Subscription and Resource Group in Azure](https://github.com/mikeguardiola/create-azure-sub-and-resource)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure

<h2>Operating Systems Used </h2>

- Windows 10 Pro (21H2)

<h2>High-Level Steps</h2>
 
- Create a Storage Account within the Resource Group
- Create a file on your local desktop and upload it into the Stprage Account
- Edit the file within the Storage Account (within the Azure Portal)
- Download the file and observe the changes

<h2>Azure Storage Account Creation: Step-By-Step Instructions</h2>

<p>
  Step 1:
<img src="https://i.imgur.com/iptUhEI.png"/>
</p>
<p>
Within the Azure Portal, navigate to the search bar at the top. Within the search bar, type "Storage accounts" and select it.
</p>
<br />

<p>
  Step 2:
<img src="https://i.imgur.com/hYekkug.png"/>
</p>
<p>
After you click "Storage accounts", you will be taken to this screen. Once there, click on "Create".
</p>
<br />

<p>
  Step 3:
<img src="https://i.imgur.com/jux9fkp.png"/>
</p>
<p>
Once you are at this screen, you can begin configuring your storage account. Under "Project Details", make sure that you have the correct subscription and resource group selected from the drop down menus. Since you are building off the previous tutorial, you can go ahead and select "Azure subsciption 1" and "resource-group-lab-01". Under "Instance Details", you will need to create a globally unique storage account name. I went with "mikecoursecareerslab01", but you can choose something that is unique to you. Next, select the correct region that most closely matches where you live. After that, you can click the "Review" button at the bottom of the screen.
</p>
<br />

<p>
  Step 4:
<img src="https://i.imgur.com/FgrJl29.png"/>
</p>
<p>
Azure will now run through a quick validation process. Once that is complete, you can click on the "Create" button at the bottom left of the screen.
</p>
<br />

<p>
  Step 5:
<img src="https://i.imgur.com/U3TxVhV.png"/>
</p>
<p>
Your storage account will now go through a deployment process which may take about 30 seconds to a minute. Once completed, you will see a green check mark next to "Your deploymeny is complete" and you can now click on the "Go to resource" button.
</p>
<br />

<p>
  Step 6:
<img src="https://i.imgur.com/gPTqYim.png"/>
</p>
<p>
You will be taken to this screen. Once there, click on "Create".
</p>
<br />

<p>
  Step 7:
<img src="https://i.imgur.com/DQAM8ke.png"/>
</p>
<p>
Now you can start configuring your resource group. Make sure that "Azure subscription 1" is selected in the first drop down menu. Next, choose a name for your resource group. You can go with "resource-group-lab-01" if you would like, or you can choose something else. Then you will want to select the region that most closely matches where you live. After that, click the "Next: Tags >" button at the bottom of the screen.
</p>
<br />

<p>
  Step 8:
<img src="https://i.imgur.com/whsN2iV.png"/>
</p>
<p>
We won't be creating any tags for this resource group, so you can go ahead and skip this step. Click on the "Next: Review + create >" button at the bottom of the screen.
</p>

<p>
  Step 9:
<img src="https://i.imgur.com/2z3qaeP.png"/>
</p>
<p>
The resource group will go through a quick validation process. Once validated, you will see a green checkmark indicating that validation has passed. Click on the "Create" button at the bottom of the screen.
</p>
<br />

<p>
  Step 10:
<img src="https://i.imgur.com/XWrsFI0.png"/>
</p>
<p>
Congratulations! You have officially created your first resource group in Azure. Go ahead an click on "resource-group-lab-01". This will take you to the portal for this resource group.
</p>
<br />

<p>
  Step 11:
<img src="https://i.imgur.com/Dv8mmwy.png"/>
</p>
<p>
This will conclude your first tutorial on how to get started using Microsoft Azure. Well done! In the next tutorial, you will be learning how to create a storage account within your resource group.
</p>
<br />
