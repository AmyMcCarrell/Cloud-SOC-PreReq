![image](https://user-images.githubusercontent.com/109401839/230745596-57cee9bd-687c-427d-b0db-d1080df77f7e.png)

# Azure Preparation

### We will create our Subscription and Resources, then go over Failed Authentication and Log Observation, and finally
Azure Active Directory Overview (Users, Groups, and Access Management)

#### Environments and Technologies Used 

- Microsoft Azure
- SQL Server
- Event Viewer

### Operating Systems Used

- VM Windows 10 PRO (21H2)

## Resources & SQL Server Vulnerabilties

<details close>

<div>

</summary>

#### Actions and Observations<b>

1. Create a Windows 10 Pro virtual machine.
2. Assign the name "(New)Honeypotlab" to the resource group.
3. Set the name of the virtual network as "honeypot-vm".
4. Double-check the virtual machine settings and proceed with creation.

#### Configure Network Security Group<b>

- Set up a Layer 4 firewall (Network Security Group) to allow all inbound traffic.
- This firewall is intentionally designed to attract threat actors such as hackers, bots, and attackers to try accessing our virtual machine.
