# Threat Detection using Open-Source SIEM Wazuh  

This project demonstrates the deployment and customization of **Wazuh**, an open-source Security Information and Event Management (SIEM) platform, to perform threat detection and monitoring in a controlled lab environment.  

---

##  Project Overview  
The objective of this project was to set up Wazuh on a VirtualBox virtual machine and evaluate its capabilities for **vulnerability assessment, log analysis, and real-time threat detection**. The project also includes the creation of **custom detection rules and dashboards** for enhanced visibility into security events.  

---

##  Implementation Steps  
- Deployed **Wazuh 4.9** on VirtualBox using a pre-configured OVA file.  
- Retrieved the server IP and accessed the Wazuh dashboard with default credentials.  
- Confirmed the **Wazuh agent** was active and transmitting logs.  

---

##  Customization & Threat Detection  
- Developed a **custom brute-force detection rule** to identify repeated authentication failures.  
- Successfully triggered alerts for brute-force attempts, confirming Wazuh’s detection capability.  
- Accessed and analyzed **real-time logs** via the Discover tab.  
- Created a **custom dashboard** to monitor SSH authentication events.  
- Categorized alerts by severity (**Medium, Low**) to support better prioritization and incident response.  

---

##  Key Outcomes  
- Functional Wazuh environment for **intrusion detection** and **log monitoring**.  
- Effective detection and visualization of **brute-force attacks** in a virtual lab.  
- Demonstrated how **open-source SIEM solutions** can be tailored for security monitoring and incident response.  

---

## ✅ Conclusion  
This project highlights how Wazuh can be leveraged as a **cost-effective, open-source SIEM** to detect, monitor, and analyze security threats. By creating **custom rules and dashboards**, Wazuh can be adapted for various security use cases in both lab and enterprise environments.  

---
