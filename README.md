# SmartBranch360 — Network Design

SmartBranch360 is a secure branch-office network project built in **Cisco Packet Tracer**.  
It showcases how enterprise branch networks can be designed with proper segmentation, security, and troubleshooting practices.  
The project includes VLANs, ACLs, NAT, DHCP, and restricted SSH access, along with documentation of fault scenarios and their fixes.

---

## 🔑 Key Highlights
- **VLAN Segmentation**: Employee (10), Guest (20), Server (30), and Management (99)
- **Guest Isolation**: ACL rules ensure Guest VLAN cannot access Server VLAN
- **Secure Management**: SSH access restricted only to Management VLAN
- **Internet Access**: NAT overload (PAT) configured for Employee and Guest VLANs
- **DHCP Pools**: Automatic IP assignment for Employee and Guest devices
- **Troubleshooting Practice**: 5 fault scenarios injected and resolved (VLAN trunk, NAT, DHCP, ACL, gateway issues)
- **Python Checker Tool**: Automated validation of VLANs, NAT, DHCP, ACLs, and static IPs

---

## 📂 Project Files
- `SmartBranch360-Networking.pkt` → Cisco Packet Tracer project file  
- `SmartBranch360_DesignDocument.docx` → Detailed design document (topology, VLAN/IP plan, ACLs, NAT, DHCP, troubleshooting notes)  

---

## ▶️ How to Use
1. Open `SmartBranch360-Networking.pkt` in Cisco Packet Tracer.  
2. Review the topology and VLAN/IP plan from the design document.  
3. Test connectivity (ping, SSH) to verify segmentation and isolation.  
4. Explore fault scenarios and apply fixes as documented.  
5. Optionally run the Python checker tool for automated validation.  

---

## 👨‍💻 Author
**Deepesh Nayak**  
B.Tech CSE (AI specialization), Medi-Caps University  
Cisco CCNA Certified | Palo Alto Firewall Intern | Python Developer
