## 🧱 Creating Virtual Machines in Microsoft Azure

In this project, I set up a dedicated resource group (`hiphop-lab-rg`) and deployed two virtual machines within the same virtual network and subnet:

- **Windows 10 VM:** Enabled with RDP for GUI access.
- **Ubuntu VM:** SSH-enabled for internal command-line access.

Both machines were configured using password-based authentication and deployed under a shared VNet (`hiphop-vnet`). This setup was used as the base infrastructure for later labs involving ICMP traffic, SSH sessions, and DNS/DHCP/RDP packet analysis via Wireshark.

📸 **Create a Resource Group**
![image](https://github.com/user-attachments/assets/226a55ac-cd43-4933-bbf9-e31da5b226ba)
📝 Description:
This screenshot shows the creation of a new Azure Resource Group (hiphop-lab-rg) in the West US 3 region. This group serves as a container for organizing and managing the resources used throughout the project.


📸 **Networking Configuration for Windows VM**
![image](https://github.com/user-attachments/assets/c87f00a9-793d-41f5-a47e-a2d00c1ec301)
📝 Description:
While setting up the Windows 10 VM, a new Virtual Network (hiphop-vnet) and Subnet (default) were created. The NIC security group was set to Basic, and RDP (3389) was enabled to allow remote desktop access.


📸 **VM Creation Summary (Ubuntu)**
![image](https://github.com/user-attachments/assets/c282de86-1abe-4d4d-bb6b-5950ba6631e8)
📝 Description:
This is the summary page before deploying the Ubuntu VM. The VM used the Standard D4s_v3 size and was deployed into the same resource group and VNet as the Windows VM. Authentication was configured using a username and password.


📸 **Ubuntu VM Deployment in Progr**
![image](https://github.com/user-attachments/assets/03055bf0-8bb3-4e78-98a8-cb8284ef8e35)
📝 Description:
Azure deployment overview for the Ubuntu Server 24.04 LTS VM. This confirms that the deployment process was successfully initiated and tracked within the Azure portal.


📸 **Logging into Windows VM via RDP**
![image](https://github.com/user-attachments/assets/ad4db72d-8a0b-45b8-8917-7182d07e8c39)
📝 Description:
This screenshot captures the login process for the Windows 10 VM using Remote Desktop Protocol (RDP). The .rdp file was downloaded from the Azure portal, and the credentials for the lab user (labuser) are entered to establish a remote session. 
