# SmartBranch360 — Secure Branch Office Network Design

SmartBranch360 is a secure branch-office network project built in **Cisco Packet Tracer**.  
It demonstrates VLAN segmentation, NAT overload, ACL-based guest isolation, and restricted SSH access for management.  
The project also includes fault-injection scenarios and a Python-based checker tool for automated validation.

---

## 🔑 Features
- **VLAN Segmentation**: Employee, Guest, Server, and Management VLANs
- **Guest Isolation**: ACL rules block Guest VLAN from accessing Server VLAN
- **Secure Management**: SSH access restricted to Management VLAN only
- **Internet Access**: NAT overload (PAT) configured for Employee and Guest VLANs
- **Troubleshooting**: 5 fault scenarios injected and resolved
- **Python Checker Tool**: Validates VLANs, NAT, DHCP, ACLs, and static IPs

---

## 📂 Project Files
- `SmartBranch360-Networking.pkt` → Cisco Packet Tracer project file  
- `SmartBranch360_DesignDocument.docx` → Detailed design document (topology, VLAN plan, ACLs, NAT, DHCP, troubleshooting notes)  
- `SmartBranch360_Demo_Video_Guide.docx` → Step-by-step demo recording script  
- Screenshots → Topology and test results  
- Optional: Demo video (`SmartBranch360_Demo.mp4`)  

---

## ▶️ How to Run
1. Open `SmartBranch360-Networking.pkt` in Cisco Packet Tracer.  
2. Test connectivity using ping and SSH commands as per the demo guide.  
3. Inject a fault (e.g., remove VLAN 20 from trunk) and verify failure.  
4. Run the Python checker tool (`checker.py`) to detect issues.  
5. Apply the fix and re-test connectivity.  

---

## 👨‍💻 Author
**Deepesh Nayak**  
B.Tech CSE (AI specialization), Medi-Caps University  
Cisco CCNA Certified | Palo Alto Firewall Intern | Python Developer
