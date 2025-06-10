## 🧱 Creating Virtual Machines in Microsoft Azure

In this project, I set up a dedicated resource group (`hiphop-lab-rg`) and deployed two virtual machines within the same virtual network and subnet:

- **Windows 10 VM:** Enabled with RDP for GUI access.
- **Ubuntu VM:** SSH-enabled for internal command-line access.

Both machines were configured using password-based authentication and deployed under a shared VNet (`hiphop-vnet`). This setup was used as the base infrastructure for later labs involving ICMP traffic, SSH sessions, and DNS/DHCP/RDP packet analysis via Wireshark.

📸 **Key Screenshots:**
![image](https://github.com/user-attachments/assets/226a55ac-cd43-4933-bbf9-e31da5b226ba)

![image](https://github.com/user-attachments/assets/c87f00a9-793d-41f5-a47e-a2d00c1ec301)
![image](https://github.com/user-attachments/assets/c282de86-1abe-4d4d-bb6b-5950ba6631e8)
![image](https://github.com/user-attachments/assets/03055bf0-8bb3-4e78-98a8-cb8284ef8e35)
![image](https://github.com/user-attachments/assets/ad4db72d-8a0b-45b8-8917-7182d07e8c39)
