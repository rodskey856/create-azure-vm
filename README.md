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
The first page is the “Basics” page, where I filled in the required fields. For the Resource group, I made a new one by selecting “Create new” and also selected an appropriate region based on my location. The location you select can affect your options for the “Size” field, so this may need to be tinkered with a little. Don’t forget to check the box under Licensing! Once I was done filling this page out, I clicked “Review + create.”
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
Out of curiosity, I viewed the various components of my new VM using Network Watcher in Azure. As you can see, when you create a VM, it’s not just the virtual machine itself that is created. Along with the VM (VM-1), Azure also created a virtual network (VM-Lab-vnet), a subnet (default), a virtual NIC (vm-1960), a Network Security Group a.k.a. firewall (VM-1-nsg), and a public IP address (VM-1-ip).
</p>
<br />

<p>
After completion, make sure you delete all resource groups. If resource groups remain running, it will deduct a fee from the free subscription!!!!
</p>
