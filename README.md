## 🧱 Creating Virtual Machines in Microsoft Azure

In this project, I set up a dedicated resource group (`hiphop-lab-rg`) and deployed two virtual machines within the same virtual network and subnet:

- **Windows 10 VM:** Enabled with RDP for GUI access.
- **Ubuntu VM:** SSH-enabled for internal command-line access.

Both machines were configured using password-based authentication and deployed under a shared VNet (`hiphop-vnet`). This setup was used as the base infrastructure for later labs involving ICMP traffic, SSH sessions, and DNS/DHCP/RDP packet analysis via Wireshark.

📸 **Key Screenshots:**
- `Azure_Resource_Group_Creation.jpeg`
- `Azure_VM_Networking_Tab_Configuration.jpeg`
- `Azure_Ubuntu_VM_Configuration_Summary.jpeg`

---
