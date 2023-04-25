<p align="center">
<img src="https://i.imgur.com/Bp7tRX1.png" height="40%" width="60%" alt="Microsoft Azure Logo"/>
</p>
<h1>Creating a Virtual Machine (VM) in Microsoft Azure</h1>
I will rehearse the steps on how to create a Virtual Machine in Azure in this project.


<h2>Requirements</h2>

- Computer w/ internet connection
- Microsoft Azure account
  - Credit card (required for free Azure credits)

<h2>High-Level Steps</h2>

- Select “Virtual machines” and select to Create an “Azure virtual machine”
- Fill in the required fields on the “Basics” page
- Click “Review + create”
- Click “Create” if the VM has passed validation
- Delete Resource Groups to minimize charges to free Azure credits

<h2>Synopsis</h2>

<p>
<img src="https://i.imgur.com/7YL2c9Z.png"/>
</p>
<p>
Step 1: First, I logged into my Azure portal account. I then searched for virtual machines in the search bar in the Azure portal. Clicked on Virtual Machines and then clicked on "Create New Virtual Machines". The Resource Group was created on its own while going trhough this process.
</p>
<br />

<p>
<img src="https://i.imgur.com/RnDe4RE.png"/>
</p>
<p>
On this page, we are creating the Virtual Machine name, choosing which region you are in, and selecting the proper image.
</p>
<p>
<img src="https://i.imgur.com/6f03xzN.png"/>
</p>
<p>
This is where we choose the right "Size" for how many Virtual Machines are required. We also added a Username and Password. These are needed if when you are opening your Virtual Machine on the Remote Desktop. Click the licensing box. I finished this section by clicking the "Review + Create" button.
</p>
<br />

<p>
<img src="https://i.imgur.com/LxnQwNJ.png" height="75%" width="75%"/>
</p>
<p>
Before the VM could be created, I had to make sure it passed validation. Once the message at the top confirmed that everything was set up properly, I clicked “Create.”
</p>
<br />

<p>
<img src="https://i.imgur.com/1dHLDbl.png"/>
</p>
<p>
It took a bit of time for the VM to be set up by Azure, but once it was done, I was able to look at the configuration of my VM. I made a mental note of the location of the public and private IP addresses on this page, since finding this information would be important for future labs.
</p>
<br />

<p>
<img src="https://i.imgur.com/WrBFPuz.png"/>
</p>
<p>
 I then went to Netork Watcher for a visual of all the components that make up the Virtual Machine. These components consist of Virtual Network, subnet (default), a virtual NIC, a network group aka Firewall, and public IP address.
</p>
<br />

<p>
After completion, make sure you delete all resource groups. If resource groups remain running, it will deduct a fee from the free subscription!!!!
</p>
