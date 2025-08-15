
#  Digital Investigation Project

**Date Completed:** 10th August 2025  
**Prepared by:** Nelson Mbua Mosisah — *Cybersecurity Analyst*

---

##  Introduction

The objective of this investigation was to analyze a **packet capture (PCAP)** file containing recent network communications.  
This file potentially held multiple artifacts, including:

- Accessed or downloaded files
- Viewed images
- Other relevant digital footprints

By systematically reviewing the network traffic, the investigation aimed to:

- Uncover the nature of the suspicious activity
- Assess potential security risks
- Document findings for incident response

This project simulated **real-world threat analysis**, providing practical experience in detecting and responding to security incidents in operational environments.

---

##  Tools Used

- **Wireshark**  
  Captured and analyzed network traffic, inspected packet exchanges related to email communication, and verified secure transmission protocols.

- **HxD Hex Editor**  
  Created sample files for attachment testing, examined file headers, and analyzed binary file structures.

- **Base64 Utility** (Python CLI)  
  Decoded Base64-encoded strings and decrypted previously encrypted email messages for further analysis.

---

##  Analysis Results

### **1. JPG File — `BNS01.JPG`**

<img width="667" height="370" alt="Screenshot 2025-08-15 215253" src="https://github.com/user-attachments/assets/06cd29fd-9e30-492d-8a04-3b9ba7feaa1c" />

- **Description:** Congratulatory image for locating a hidden visual during the internship exercise.
- **Contents:** Lead trainer *Ali S. Benson* in a cybersecurity-themed setting representing the **Network Traffic Analysis** module.

---

### **2. PNG File — `BNS02.PNG`**
- **Description:** Official **BNS Cyberlab Limited** logo.
- **Use Case:** Featured in internship documentation and reporting.

---

### **3. PDF File — `BNS03.PDF`**
- **Description:** Document explaining **Network Traffic Analysis** concepts and its cybersecurity role.
- **Highlights:**
  - Definition and importance of Network Traffic Analysis
  - Applications in detecting threats, monitoring anomalies, incident investigation, and compliance

---

### **4. ZIP File — `BNS04.ZIP`**
- **Description:** Additional project files and materials.
- **Possible Contents:**
  - Raw datasets
  - Sample `.eml` files for parsing
  - PCAPs for analysis
  - Other relevant project artifacts

---

##  Conclusion

This investigation applied **cybersecurity principles and technical skills** to a practical, real-world challenge.  
Key takeaways:

- Integrated **threat intelligence**, **malware analysis**, and **email parsing** into an automated workflow.
- Gained experience in:
  - Managing raw network data
  - Decoding encrypted content
  - Monitoring activity linked to email processing
- Reinforced the importance of **structured, tool-assisted analysis** to combat evolving cyber threats.

By leveraging **Wireshark**, **HxD**, and **Base64 decoding**, the project successfully achieved its goals while building a functional cybersecurity automation workflow.

