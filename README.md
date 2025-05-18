# 🛡️ Network Penetration Testing with Real-World Exploits and Security Remediation

This project simulates **real-world network attacks and defense strategies** using **Kali Linux** as the attacker machine and **Metasploitable 2** as the vulnerable target. All tasks are performed in a controlled lab environment for **educational and ethical purposes**.

---

## 🎯 Objectives

- Simulate real-world network attacks in a safe environment  
- Perform scanning, enumeration, and exploitation using industry tools  
- Crack Linux password hashes using **John the Ripper**  
- Identify outdated or vulnerable services  
- Recommend and implement security remediations  

---

## 📂 Project Contents

- 📄 `CEH_Project_By_Mahtab.pdf` – Full project report with screenshots and command outputs  
- 🖼️ `Screenshots/` – Real-time evidence of network attacks and security defenses *(to be uploaded)*

---

## 💻 Lab Setup

### 🖥️ Operating Systems

- **Kali Linux** – Attacker machine  
- **Metasploitable 2** – Target machine  

### 🛠️ Tools Used

| Tool              | Purpose                                   |
|-------------------|-------------------------------------------|
| `nmap`            | Port scanning, OS detection, service versioning |
| `Metasploit`      | Exploitation framework                   |
| `John the Ripper` | Password hash cracking                   |
| Linux CLI         | User management and enumeration           |

---

## 🚀 Tasks Performed

### 🔍 Network Scanning (Using `nmap`)

```bash
nmap -v <IP>           # Basic scan  
nmap -v -p- <IP>       # Full port scan  
nmap -sV <IP>          # Service version detection  
nmap -O <IP>           # OS detection  

