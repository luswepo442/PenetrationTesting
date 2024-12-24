# Ethical Hacking Project Report

**Author:** Luswepo Daniel Sinyinza  
**Objective:** Practice ethical hacking techniques to assess vulnerabilities and improve the security of my host device (Mac) using Kali Linux.

---

## Project Overview  
This project focuses on ethical hacking techniques, including network and port scanning, service enumeration, and vulnerability analysis. Using tools such as Nmap, Gobuster, and cURL, I analyzed the host device to identify open ports, running services, and potential misconfigurations.

---

## PHASE 1: Network and Port Scanning  
### Tools Used  
- **Nmap**: For network scanning and service enumeration.  
- **Gobuster**: For directory brute-forcing (optional).  
- **cURL**: For interacting with HTTP services.

### Key Steps  
1. **Basic Network Scan**: Verified connectivity between the Kali Linux VM and the host device.  
2. **Port Scanning**: Identified open ports (80, 5000, 7000) and enumerated running services.  
3. **Service Enumeration**: Used Nmap scripts to gather detailed information about services.

---

## PHASE 2: Results of Port Scans  
### Open Ports and Services  
- **Port 80 (HTTP)**: Directory listing under `/icons/` and restricted access to certain files.  
- **Port 5000 (UPnP)**: Potential misconfigurations exposing network configurations.  
- **Port 7000 (AFS3 Fileserver)**: Limited initial information.

---

## PHASE 3: Analysis and Next Steps  
### Port 80 (HTTP)  
- **Findings**: Misconfigured directory access and potential outdated web server software.  
- **Next Steps**:  
  - Explore accessible directories and files.  
  - Research vulnerabilities related to the web server.  

### Port 5000 (UPnP)  
- **Findings**: Potential exposure of sensitive network configurations.  
- **Next Steps**:  
  - Perform deeper enumeration using UPnP tools.  
  - Investigate known UPnP vulnerabilities.  

### Port 7000 (AFS3 Fileserver)  
- **Findings**: Limited information available from the initial scan.  
- **Next Steps**:  
  - Further probe using Nmap scripts.  
  - Research AFS3-related vulnerabilities.

---

## PHASE 4: Summary of Findings  
1. **Port 80 (HTTP)**: Misconfigurations and accessible directories present security risks.  
2. **Port 5000 (UPnP)**: Potential vulnerabilities due to service misconfiguration.  
3. **Port 7000 (AFS3 Fileserver)**: Requires further investigation to uncover potential risks.

---

## Future Work  
This project will continue with an in-depth focus on:  
- Exploiting potential vulnerabilities on the HTTP service.  
- Addressing risks associated with UPnP misconfigurations.  
- Investigating AFS3 weaknesses to enhance the security posture of the host device.

---

## Disclaimer  
This project is conducted in a controlled environment with proper authorization. It is intended for educational and ethical purposes only.
