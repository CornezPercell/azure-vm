<p align="center">
<img src="https://github.com/CornezPercell/azure-vm/blob/main/AZURE.png"/>
</p>

<h1>Configuring a virtual machine and remote desktop (Azure)</h1>
This tutorial outlines the implementation of Azure Virtual Machines and remote desktop.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop


<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 



<h2>Deployment and Configuration Steps</h2>
<h2>CREATING VIRTUAL MACHINE</h2>

![image](https://github.com/CornezPercell/azure-vm/blob/main/Screenshot%20(317).png)
1. Visit Azure
- Go to azure.microsoft.com.

2. Sign Up for a Free Account
- Sign up for a free 30-day subscription.
- Create a username and password for your tenant.
- Access the portal anytime at portal.azure.com using your credentials.






3. Create a Resource Group
- In the search bar, type "Resource Groups" and click on "Create Resource Group".
![image](https://github.com/CornezPercell/azure-vm/blob/main/Screenshot%20(319).png)

- Enter a name for your resource group.
- Under "Resource Details," choose your desired region.
- Click "Review + Create." After validation, click "Create" to set up the resource group.
![image](https://github.com/CornezPercell/azure-vm/blob/main/Screenshot%20(322).png)




4. Create a Virtual Machine
- In the search bar, type "Virtual Machines."
![image](https://github.com/CornezPercell/azure-vm/blob/main/Screenshot%20(323).png)

- Click "Create," then select "Azure Virtual Machine."
![image](https://github.com/CornezPercell/azure-vm/blob/main/Screenshot%20(324).png)

- In the creation form:
- Select your Azure Subscription and the Resource Group you just created.
- Name your Virtual Machine.
- Choose the same region as your resource group.
![image](https://github.com/CornezPercell/azure-vm/blob/main/Screenshot%20(325)2.PNG)

- Select your desired Operating System under "Image."(windows 10 )
- Pick the desired and compatible Size for your virtual CPU.(minumum 2 vcpus and 8gb of memory)
![image](https://github.com/CornezPercell/azure-vm/blob/main/Screenshot%20(329).png)


- Create a username and password for the Administrator account.
- Be sure to keep a record of your name and password that was created.

![image](https://github.com/CornezPercell/azure-vm/blob/main/Screenshot%20(332).png) 
-Check the licensing box.
Click "Review + Create." After validation, click "Create." This may take a few minutes.

![image](https://github.com/CornezPercell/azure-vm/blob/main/Screenshot%20(333).png).png)

![image](https://github.com/CornezPercell/azure-vm/blob/main/Screenshot%20(334).png)


Congratulations on creating your Virtual Machine!

 
 <h2>Remote access</h2>


1. Access Your Virtual Machine
- In the search bar, type "Virtual Machines" or find it under the "Azure Services" tab.
- Click on the name of the VM you created to access the overview page.
![image](https://github.com/CornezPercell/azure-vm/blob/main/Screenshot%20(338).png)

- Note the Public IP Address displayed.
![image](https://github.com/CornezPercell/azure-vm/blob/main/Screenshot%20(340).png)




2. For Windows Users
- Open the Start menu and type "Remote Desktop."
 <img src="https://github.com/CornezPercell/azure-vm/blob/main/Screenshot%20(341).png" height="60%" width="60%">

- Login to the Virtual Machine using the public ip address of the Virtual Machine, Click Show options to type in username
- Paste or type the public IP address into the Remote Desktop Connection window.
- 
 <img src="https://github.com/CornezPercell/azure-vm/blob/main/Screenshot%20(342).png" height="60%" width="60%">


- Click connect, type in the password when prompted.
-  <img src="https://github.com/CornezPercell/azure-vm/blob/main/Screenshot%20(343).png" height="60%" width="60%">

<img src="https://github.com/CornezPercell/azure-vm/blob/main/Screenshot%20(344).png" height="60%" width="60%">

- 

- 
- If you receive a warning about security, click Yes to proceed.
- Your Virtual Machine should load

<img src="https://github.com/CornezPercell/azure-vm/blob/main/Screenshot%20(346).png" height="60%" width="60%">

- Connecting to Your VM


![image](https://github.com/user-attachments/assets/4860d276-db2c-4de3-a870-1e1ea34048b4)



3. For Mac Users
- Download "windows app" from the App Store (it's free).
![image](https://github.com/user-attachments/assets/5225a579-c0df-471d-a912-30c2bce1459b)


- Open the app and click the + sign to Add PC.
![image](https://github.com/user-attachments/assets/a950947a-cc2d-404c-bb54-a1df316fdf06)


- Enter the public IP address under "PC Name."
![image](https://github.com/user-attachments/assets/b9c7114d-9459-4ba6-abe1-da0ec58dc4ae)



- Under "Saved PC," enter the VM's username and password.
- Click continue.
![image](https://github.com/user-attachments/assets/2a52a822-9186-450c-adb5-cb7fe9ae0578)

4. Connecting to Your VM
![image](https://github.com/user-attachments/assets/6773ccfd-31b0-40eb-bd90-161b7e6e8820)


<h2>Deleting Your Virtual Machine</h2>

1. To delete your VM and associated resources:
- Go back to the Azure portal.
![image](https://github.com/user-attachments/assets/c72b1037-3cbe-4e31-822a-fe81319e2124)

- Navigate to your Resource Group.
- Delete the resource group and any related folders (e.g., NetworkWatcherRG).
(RG-network-activitie)
![image](https://github.com/user-attachments/assets/ff63b762-f0b5-46d9-955e-1d537c2d9119)


And that's it! You've successfully created, accessed, and deleted a Virtual Machine on Azure.
