
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
### Use Wireshark to capture network activity and export the relevant packets: ( eg, HTTP file transfer) ### 

<img width="1919" height="337" alt="Capture network traffic" src="https://github.com/user-attachments/assets/898bba45-68f9-4c03-8066-f2b680b373f1" /> 


### Identify files, right click> follow> TCP stream,

<img width="1066" height="304" alt="TCP Stream" src="https://github.com/user-attachments/assets/b5eaac6c-37b8-498c-93e4-c0441a272c45" />


### Open the exported data in HxD. -Identify file signatures (e.g., PNG: 89 50 4E 47, JPG: FF D8 FF, PDF: %PDF, ZIP: 50 4B 03 04).


<img width="1854" height="755" alt="HxD  Analysis" src="https://github.com/user-attachments/assets/c39fff35-2729-4cee-b834-ed2e74d3637c" />






### **1. JPG File — `BNS01.JPG`**

<img width="667" height="370" alt="Screenshot 2025-08-15 215253" src="https://github.com/user-attachments/assets/06cd29fd-9e30-492d-8a04-3b9ba7feaa1c" />

- **Description:** Congratulatory image for locating a hidden visual during the internship exercise.
- **Contents:** Lead trainer *Ali S. Benson* in a cybersecurity-themed setting representing the **Network Traffic Analysis** module.

---

### **2. PNG File — `BNS02.PNG`**
<img width="364" height="364" alt="Screenshot 2025-08-15 215448" src="https://github.com/user-attachments/assets/a3ffa211-60bd-4f47-b581-dde1d7a4a9de" />


- **Description:** Official **BNS Cyberlab Limited** logo.
- **Use Case:** Featured in internship documentation and reporting.

---

### **3. PDF File — `BNS03.PDF`**

<img width="716" height="399" alt="Screenshot 2025-08-15 215528" src="https://github.com/user-attachments/assets/42a62ee9-d4da-438f-adfe-bb722c795ca0" />

- **Description:** Document explaining **Network Traffic Analysis** concepts and its cybersecurity role.
- **Highlights:**
  - Definition and importance of Network Traffic Analysis
  - Applications in detecting threats, monitoring anomalies, incident investigation, and compliance

---

### **4. ZIP File — `BNS04.ZIP`**
<img width="504" height="703" alt="Screenshot 2025-08-11 001833" src="https://github.com/user-attachments/assets/4224e50b-fd9c-4bfa-bf39-f6e4e048eeb7" />


<img width="1342" height="809" alt="Screenshot 2025-08-11 001231" src="https://github.com/user-attachments/assets/3c19a511-1c32-493d-9ef3-53feeb9ad18f" />

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

