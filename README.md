# 🚀 Alberta-Hamilton Enterprise Branch Lab

### **Project Goal**
Design and implement a redundant, secure network architecture connecting a Hamilton-based SOHO to an Alberta branch.

### **Key Features**
* **Redundancy:** HSRP (Hot Standby Router Protocol) with Preempt for instant gateway failover.
* **Routing:** OSPF Area 0 for dynamic link discovery between branches.
* **Security:** Port Security (Sticky MAC) and Extended ACLs for guest isolation.
* **Management:** Encrypted SSH access using RSA keys.

### **How to Use**
Download the `.pkt` file and open it in **Cisco Packet Tracer 8.x** to view the full topology and configurations.
### Update: OSPF Triangle Complete
* Successfully linked Ottawa, Hamilton, and Alberta routers using OSPF Area 0.
