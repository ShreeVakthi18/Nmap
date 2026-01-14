# Network Reconnaissance & Attack Surface Assessment

## Overview
This lab demonstrates **practical network reconnaissance** using Nmap.  
The objective is to understand how port scanning and OS detection are used to assess a system’s **network exposure and attack surface**.

---

## Tool & Environment
- **Tool:** Nmap  
- **Operating System:** Ubuntu Linux (WSL)  
- **Target:** Self system (local network IP)

---

## Methodology
1. Performed basic TCP port scanning to identify open and closed ports  
2. Used service version detection with the `-sV` option  
3. Conducted OS detection using the `-O` option with root privileges  

---

## Observations
- The host was reachable on the network  
- All common TCP ports were found to be closed  
- No unnecessary services were exposed, indicating a hardened system  
- OS detection accuracy was limited due to the absence of open ports  

---

## Result
Successfully assessed the system’s network exposure using Nmap and identified a **minimal attack surface**.

---

## Ethical Notice
This lab was conducted only on my **own system** in a controlled environment.  
No unauthorized scanning of external systems was performed.

---

## Key Learnings
- Practical use of Nmap for port scanning and enumeration  
- Understanding how open ports contribute to an attack surface  
- Limitations of OS detection when services are not exposed  
- Importance of attack surface reduction for system security  

---

## Author
Computer Science undergraduate focused on cybersecurity fundamentals and network defense.
