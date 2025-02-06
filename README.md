<p align="center">
<img src= "https://github.com/user-attachments/assets/47310552-28f2-4b6f-bdc6-761a7e1175b0"/>

</p>

<h1>Azure - Creating a VM (Virtual Machine)</h1>
This outlines the process of creating a VM (Virtual Machine) using Azure.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)

<h2>Operating Systems Used </h2>

- Windows 10</b>

<h2>Post-Install Configuration Objectives</h2>

- Create a Resource Group
- Creat a Windows 10 VM
- Validate VM has correct settings
- Complete

<h2>Configuration Steps</h2>

<p>
<img src="https://github.com/user-attachments/assets/6f7bd52c-1876-4a95-aae3-b68400c84243" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
When you have created an Azure account, go to "portal.azure.com". Here we can, at the top of the page, search for and create a "Resource Group".
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/6ecacede-eb3c-41bc-a209-2fba79dc62a6" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Here we are creating the resource group. We make sure we give it a name, I chose mine as "vm-test1, you can name it how you prefer. Next we need to select the correct region in which we live most nearest to, this will ensure we have the best connection to our VMs.
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/5032df22-3d01-429b-a246-d35f9ef9e2b8" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
When you have correctly named and selected your region at the bottom of the page you can select the "Next" button and here on this page we can add "users" to this VM. For this example i have given here the name of "Owner" and just assigned an Email address to it. Once complete please locate the "Next" button at the bottom of the page again.
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/5a82b64b-0027-4553-b6eb-4082c1f3764c" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
We cab see here it was successful, at the bottom of the page we can now click on "Create". This may take some time.
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/1793ea4f-3447-45de-b214-2c8393d49b76" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://github.com/user-attachments/assets/58a8f6df-a1f6-4a39-9545-9a1578006202" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://github.com/user-attachments/assets/967d389f-18ce-4661-a9b1-5b2685cf6cc5" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<p>
<img src="https://github.com/user-attachments/assets/dc746eb3-614a-4c88-ac01-4c2a02ad21e6" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
One correction needs to be made here, Theres a section called Project Details and there you can see the Availability Zone. This needs to be changed from "Zone 1" to "Zone 2". If this doesnt get changed the VM does not start and errors will occure with the settings i have given you in this tutorial.
</p>
<br />
  
<img src="https://github.com/user-attachments/assets/e7089df8-ebcf-4901-b7d3-bd1ef1e85841" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now when it is created you should see the name of your resource group there, mine is named "vm-test1" as per the tutorial. We can click on it and then at the top there will be a "create" button and we will search for "Microsoft Windows 10". We need to give the vm a name, set a username and password and make sure the region is selected correctly on this screen and also check the box at the bottom for the authentic windows 10 key. Once that is done we can hit review and create at the bottom, once it completes you can hit the Create button again.
</p>
<br />
