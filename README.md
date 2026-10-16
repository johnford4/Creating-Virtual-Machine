
<img width="738" height="252" alt="image" src="https://github.com/user-attachments/assets/b2e319a7-b513-41eb-a717-cde303917c24" />

# Deploying a Windows 11 Virtual Machine in Microsoft Azure

## Project Overview

In this project, I used Microsoft Azure to create and deploy a Windows 11 virtual machine.

The purpose of this project was to gain hands-on experience with cloud computing and learn how to create and configure a virtual machine using the Microsoft Azure portal.

This project was completed as part of my CourseCareers Information Technology training.

## Technologies Used

- Microsoft Azure
- Azure Virtual Machines
- Windows 11 Pro
- Azure Resource Groups
- Azure Virtual Networking
- Azure Portal

## Virtual Machine Specifications

| Component | Configuration |
|---|---|
| Cloud Provider | Microsoft Azure |
| Operating System | Windows 11 Pro |
| Virtual Machine Name | vm-it-portfolio |
| Resource Group | rg-it-portfolio |
| VM Size | Standard_D2ds_v7 |
| Virtual CPUs | 2 |
| RAM | 8 GB |
| Deployment Method | Azure Portal |

---

## Step 1: Accessing Microsoft Azure
<img width="2549" height="1348" alt="01-Azure-Portal-Home" src="https://github.com/user-attachments/assets/0602bee7-289b-4a05-bcef-111fd7a0655c" />

I started by opening my web browser and navigating to the Microsoft Azure portal.

Website: https://portal.azure.com/

After signing in to my Microsoft account, I was taken to the Azure dashboard, where I could access the different cloud services.



## Step 2: Finding Virtual Machines
<img width="545" height="418" alt="02-Finding-Virtual-Machines" src="https://github.com/user-attachments/assets/5605472b-e82c-4211-b65c-732270e68d9c" />

From the Azure dashboard, I clicked the search bar at the top of the page and typed **Virtual machines**.

The Virtual Machines service appeared in the search results.

I selected this service to access the virtual machine management page.


## Step 3: Creating a New Virtual Machine
<img width="390" height="322" alt="03-Virtual-Machines-Page" src="https://github.com/user-attachments/assets/dbab24a6-0fc2-4cc5-bce4-d2cdc71fd7fa" />

After opening the Virtual Machines page, I located the **Create** button.

I clicked Create and selected **Azure virtual machine** to begin the setup process.


## Step 4: Configuring the Virtual Machine
<img width="1017" height="923" alt="04-VM-Basics-Configuration" src="https://github.com/user-attachments/assets/78f99b28-3bd5-4502-9a78-4b5c96569101" />

On the Basics tab, I entered the information needed to create my virtual machine.

I created a resource group to organize the resources associated with my project.

I configured the following settings:

- **Resource Group:** rg-it-portfolio
- **Virtual Machine Name:** vm-it-portfolio
- **Operating System:** Windows 11 Pro

The Basics tab allowed me to select the operating system and configure the virtual machine before deployment.


## Step 5: Selecting the Virtual Machine Size
<img width="774" height="840" alt="05-VM-Size-Selection" src="https://github.com/user-attachments/assets/d842caf9-73a4-429e-91c3-ca0f78493948" />

Next, I selected the hardware configuration for my virtual machine.

I chose **Standard_D2ds_v7**, which includes:

- 2 virtual CPUs
- 8 GB of RAM

I selected this configuration for my Windows 11 virtual machine deployment project.


## Step 6: Configuring Networking
<img width="808" height="1178" alt="06-VM-Networking-Configuration" src="https://github.com/user-attachments/assets/adb99554-60f6-48cf-a500-e5fbaae551a7" />

Next, I opened the Networking tab.

This section is used to configure the virtual machine's network connectivity.

The Networking tab includes options for:

- Virtual networks
- Subnets
- Public IP addresses
- Network security groups
- Inbound network ports

I proceeded through the networking settings before reviewing the deployment.


## Step 7: Reviewing the Virtual Machine
<img width="805" height="1149" alt="7 VM-Review-And-Create" src="https://github.com/user-attachments/assets/b8ec8279-08da-42ab-b4fb-969f0f4855f7" />

After completing the configuration screens, I selected **Review + create**.

This allowed me to review the virtual machine configuration before deployment.

Azure performed a validation check on the selected settings.

I then proceeded with creating the virtual machine.


## Step 9: Deploying the Virtual Machine
<img width="986" height="451" alt="8 VM-Deployment-Complete" src="https://github.com/user-attachments/assets/304a8a9f-f49d-47ce-bcf4-5e7482d5018c" />
After reviewing the configuration, I clicked **Create**.

Microsoft Azure began deploying the Windows 11 virtual machine.

I waited for Azure to finish provisioning the resources.

Once the deployment finished, Azure displayed the message:

**"Your deployment is complete."**

This confirmed that the virtual machine had been successfully deployed.

---