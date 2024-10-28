<p align="center">
<img src="https://i.imgur.com/a1mJAFV.png="40%" width="40%" alt="Microsoft Azure Logo"/>
</p>

<h1>Microsoft Azure</h1>
Azure is a cloud service from Microsoft that lets you use and manage various online tools and resources. To start using Azure, you just need an internet connection and access to the Azure website. This guide will show you how to set up an Azure account and create a virtual machine, which is like a computer you can use online.

<h2>Requirements</h2>

- Computer with Internet Connection
- Credit Card (Required for free Azure credits)

<h2>Configuration Steps</h2>


<h3>Step 1: Create an Azure Account</h3>


Create an Azure account [here](https://azure.microsoft.com/en-us/free/).
- Select Start Free
- Follow the prompt to create the account 
     - You will need to put in your credit card information, but you will get $200 worth of Azure credit and will have 30 days to use those credits. You will not be charged until then
- Finish the prompt, click Go to Azure Portal, and you are ready to start with Azure!
  
<h3>Step 2: Create a Virtual Machine</h3>

- Go to the search bar and search "virtual machine"
- Select Create, then select Azure Virtual Machine
- You will need to select the same resource group, the same region, and create a name for the virtual machine
    - For thise example, we will name the virtual machine "virtualmachine"
    - Use the same resource group and region as steps 2 and 3

<p align="center">
<img src="https://i.imgur.com/55s8gku.png" height="70%" width="70%" alt="Azure Free Account"/>    <img src="https://i.imgur.com/Az8GoTu.png" height="50%" width="50%" alt="Azure Free Services"/>
</p>
 



* You will then need to select the image and disk size
    - For image we will use Windows 10 Pro
    - For size, select See All Sizes and select Standard D2as_v4
* You will then need to make a username and password
    - For username, we will use "labuser"
    - Create your own password
* Click the box under licensing and finally click Review + Create 


<p align="center">
<img src="https://i.imgur.com/p9UJXND.png" height="70%" width="70%" alt="Azure Free Account"/> <img src="https://i.imgur.com/GHBDae0.png" height="70%" width="70%" alt="Azure Free Services"/>
</p>
 
     

<h3>Step 5: Connect to the Virtual Machine</h3>

- First, you will need to find the public IP address of your virtual machine
   - Select the virtual machine we created and the public IP address will be on the right-hand side of the screen
   - Copy the public IP address

<p align="center">
<img src="https://i.imgur.com/T4Oc2RX.png" height="80%" width="80%" alt="Azure Free Account"/>

* Mac Users 
   - Download Microsoft Remote Desktop
   - Open the application and click Add PC
   - Paste the public IP address and select Add
   - Double-click on the virtual machine and enter the username and password from step 4
   - Select Continue
   
* Windows Users
     - Open and use Remote Desktop
     - Paste the public IP Address and select Connect
     - Enter the username and password from step 4
     - Select OK
  
     
     
 <p align="center">
<img src="https://i.imgur.com/14pPOdv.png" height="70%" width="70%" alt="Azure Free Account"/> <img src="https://i.imgur.com/Og3LKyd.png" height="70%" width="70%" alt="Azure Free Services"/>
</p>





🎉Congratulations! You have created your first virtual machine within Azure!🎉

<p align="center">
<img src="https://i.imgur.com/rEBpL8Y.png" height="80%" width="80%" alt="Azure Free Account"/>

<h3>Tip</h3>

-  If you want to save your free $200 credits, make sure you delete ALL your resources and resource groups after finishing! 
