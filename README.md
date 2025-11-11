# 🖧 Introduction to Networking – Server Configuration & ACL Implementation

## 📌 Project Overview
This networking project focuses on configuring and securing access to a new **HTTP-enabled server** within the Admin network (`192.168.10.5`). The objective was to apply Access Control Lists (ACLs) that allow only the **Admin** and **Sales** departments to connect to the server while completely denying access from the **HR department**. The project includes network setup, configuration steps, and validation using connectivity tests and screenshots.

---

## 🛠 Tools Used
- **Cisco Packet Tracer**  
- **Router & Switch CLI**  
- **DNS/DHCP Server Configuration Tools**  
- **PC Command Prompt for Ping Tests**  
- **HTTP Server Module**  
(All referenced from descriptions within the submitted documentation.)

---

## 🧰 Technologies & Concepts Applied
- Subnetting and IP Assignment  
- DHCP Configuration (Static and Dynamic)  
- Router Interface Configuration  
- Access Control Lists (ACLs)  
- DNS Setup  
- Network Design and Topology Creation  
- Connectivity Testing (Ping)  
- HTTP Service Configuration 

---

## 🧱 Network Design Summary
The network topology consists of separate departmental networks: **Admin**, **Sales**, and **HR**, each with their switches and PCs. All departments connect to a central router. The server is connected to the Admin switch. Devices were dragged into the workspace, connected via automatic wiring, and configured with the appropriate IP addressing. DHCP pools were created for each department, and router interfaces were configured using CLI. 

---

---

## ✅ Key Results & Observations
- HR department access to the server was successfully denied.  
- Admin and Sales departments were able to establish HTTP connections.  
- ACL rules correctly filtered and controlled traffic.  

---

## 🔐 How ACLs Improved Security
Access Control Lists ensured that only authorized clients could access network resources. They filtered traffic based on rules, blocking unauthorized connections and reducing the risk of malicious activity. By enforcing strict traffic control, ACLs enhanced the network’s integrity and protected sensitive sectors from improper access.

---

## 🏁 Conclusion
ACLs are critical tools in network administration, enabling secure segmentation by allowing or denying traffic at a granular level. Properly configured ACLs help protect servers and sensitive data from unauthorized access while ensuring that trusted devices communicate efficiently. They form an essential layer of defense in modern network management and security practices.

---


