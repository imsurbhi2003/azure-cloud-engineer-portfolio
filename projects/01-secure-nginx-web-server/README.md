Secure NGINX Web Server on Microsoft Azure
Project Overview
This project demonstrates the deployment and securing of an Ubuntu-based NGINX web server on Microsoft Azure.
The solution uses Azure Virtual Network, a dedicated subnet, a subnet-level Network Security Group, a public IP, SSH key-based authentication, and an Ubuntu 22.04 virtual machine.
Architecture
Internet → Public IP → Network Security Group → Web Subnet → Ubuntu VM → NGINX
Azure Services Used
Azure Resource Group
Azure Virtual Network
Azure Subnet
Network Security Group (NSG)
Azure Virtual Machine
Public IP Address
Network Interface
Ubuntu Linux
NGINX
Security Configuration
HTTP allowed on TCP port 80
SSH allowed on TCP port 22 only from the administrator source IP
SSH key-based authentication used for VM administration
NSG associated with the web subnet
Project Status
Deployment successful
SSH connectivity verified
NGINX installed and running
Website accessible through the public endpoint
Custom interactive webpage deployed
Author
Surbhi Kumari
 
