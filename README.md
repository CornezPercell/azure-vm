<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>Create a Virtual Machine and access it with Remote Desktop</h1>
This tutorial outlines the process of  setting up a Virtual Machine with using Microsoft Azure and how to navigate it using remote desktop<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Have a Microsoft Azure Account.
- Create Windows 10 Virtual Machine
- Access VM with Remote Desktop
- Download osTicket installation files
- Get familiar with IIS (Internet Information Services)

<h2>Installation Steps</h2>

<img src="https://github.com/CornezPercell/osticket-prereqs/blob/bd5b3432d100f7272cebc926936f1f218d48d9cb/Screenshot%20(177).png" height="80%" width="80%">
</p>
<p>
After setting up a Microsoft Azure account and subscription, create a Windows 10 Virtual Machine with a minimum of 4 vCPUs. A username and password will be needed to log in
on the VM, be sure to create and store the username and password so that the correct information is accessible, as it will be needed to log in using Remote Desktop.
  
</p>
<br />

<p>
<img src="https://github.com/CornezPercell/osticket-prereqs/blob/main/Screenshot%20(268).png" height="40%" width="40%">
</p>
<p>
After setting up the VM copy or make note of the public ip address as it will be used to log into remote desktop. Open desktop on your computer,
  on a windows computer you can find it by opening the windows button and searching "mstsc". Login using credentials created on Azure. Type or paste public ip address
  where it ask for computer, when it prompts for password, use the one created in Azure for the VM.
</p>
<br />

<p>
<img src="Screenshot (272).png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After successfully logging into the VM, open the web browser and go to osticket.com. You will need to download the files to install OS ticket onto the VM.
  This picture shows all the files I used for this setup. You can access these files HERE.
<br />
After succesfully downloading and installing these compononents we are now ready to configure OS ticket so you can create your own ticketing system.
For my guide to Post installation and configuration, click here.
