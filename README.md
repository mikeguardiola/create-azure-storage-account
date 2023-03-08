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
<img src="https://i.imgur.com/FDh8Umj.png"/>
</p>
<p>
First, you will need to navigate to https://azure.microsoft.com/en-us/free/. Click on the green "Start Free" button to create your Azure account.
</p>
<br />

<p>
  Step 2:
<img src="https://i.imgur.com/m21ZVwI.png"/>
</p>
<p>
Once you have gone through the entire process of creating your account and your account verification is complete, you can go ahead and navigate to the Azure Portal. If you ever have difficulty finding the Azure Portal, you can always access it by typing https://portal.azure.com into your web browser.
</p>
<br />

<p>
  Step 3:
<img src="https://i.imgur.com/HiWBPue.png"/>
</p>
<p>
After you are in the Azure Portal, you will want to verify that an active subscription was created. Go to the search bar within the portal and type "Subsciptions". Click on the search result titled "Subscriptions" with the gold key next to it.
</p>
<br />

<p>
  Step 4:
<img src="https://i.imgur.com/np0vgG1.png"/>
</p>
<p>
You will be taken to this screen where we can see that "Azure Subscription 1" has been created. On the far right side, you can see that status of the subscription is "Active".
</p>
<br />

<p>
  Step 5:
<img src="https://i.imgur.com/UWGG5v9.png"/>
</p>
<p>
Next, you will go ahead and create your first Resource Group in Azure. To do this, navigate to the portal search bar and type "Resource groups". Click on "Resource groups".
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
