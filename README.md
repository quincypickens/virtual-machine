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

- Go to the search bar and search "virtual machine."
- Select Create, then select Azure Virtual Machine.
- Create a resourse group.
- Name your virtual machine.
- Select a region.
- Select Windows 10 pro for image.

<p align="center">
<img src="https://i.imgur.com/55s8gku.png" height="70%" width="70%" alt="Virtual Machine Lab"/> <img src="https://i.imgur.com/Az8GoTu.png" height="50%" width="50%" alt="Virtual Machine Lab"/> <img src="https://i.imgur.com/Bnil76b.png" height="50%" width="50%" alt="Virtual Machine Lab"/>
</p>
 
* You will then need to select disk size.
    - If possible select a size with at least 2 vcpus and 8 GIBs.
* You will then need to create a username and password.
* Click the box under licensing and finally click Review + Create. 

<p align="center">
<img src="https://i.imgur.com/4xsJJB1.png" height="70%" width="70%" alt="Virtual Machine Lab"/> 
</p>
 
<h3>Step 3: Connect to the Virtual Machine</h3>

- You will need the public IP address of your virtual machine
   - Select the virtual machine you created and the public IP address will be on the right-hand side of the screen
   - Copy the public IP address

<p align="center">
<img src="https://i.imgur.com/96jxGGg.png" height="100%" width="100%" alt="Virtual Machine Lab"/>

* Mac Users 
   - Download Microsoft Remote Desktop
   - Open the application and click Add PC
   - Paste the public IP address and select Add
   - Double-click on the virtual machine and enter the username and password from step 4
   - Select Continue
   
* Windows Users
     - Type Remote Desktop Connections in you search bar.
     - Paste the public IP Address and select Connect
     - Enter the username and password from step 4
     - Select OK
  
   <img src="https://i.imgur.com/4oIgv1O.png" height="50%" width="50%" alt="Virtual Machine Lab"/>  

You have created your first virtual machine within Azure!

<p align="center">
<img src="https://i.imgur.com/jjJmcNg.png="60%" width="60%" alt="Azure Free Account"/>

