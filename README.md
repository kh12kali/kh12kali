# Hi, I'm Danyal Hussain 👋

**CS Student · Digital Forensics · Cybersecurity · Ethical Hacking**

Bachelor's student in Computer Science at **Guizhou University, China**.  
Passionate about cybersecurity, digital forensics, and building security tools.  
Currently working on a **Website Security Scanner SaaS** 

---

## 🛡️ Skills

**Forensics & Investigation**
- Disk image analysis · File carving · Timeline reconstruction · Evidence preservation
- Tools: Autopsy · FTK Imager · HxD Hex Editor · OSForensics · HashMyFiles

**Network Security & Intrusion Detection**
- IDS/IPS configuration · Attack simulation · Packet analysis · SIEM monitoring
- Tools: Suricata · Snort · Wazuh · Wireshark · pfSense · Kali Linux

**Ethical Hacking & Penetration Testing**
- Brute force · SQL injection · ARP spoofing · Reverse shell · DDoS simulation
- Tools: Metasploit · SQLMap · Burp Suite · Netcat · Nmap

**Network Administration**
- DHCP · RIPv2 · SSH · Router/Switch configuration · Windows Server · Active Directory

**Programming**
- Python · C / C++ · Bash scripting · Data analysis

---

## 📁 Projects

### 🔴 Operation Rio Grande — Forensic Investigation *(Featured)*
Full police-style digital forensic investigation of a real criminal case scenario.

- Verified disk image integrity using MD5 and SHA1 hashing (chain of custody)
- Reconstructed full timeline of suspect activity using Autopsy
- Cracked a 3-password chain across encrypted files, RAR archives and ZIP folders
- Detected steganography and hidden data within image files using OpenPuff
- Identified and categorised illegal content with proper evidence handling procedures
- Produced a court-ready forensic report following PACE guidelines

**Tools:** Autopsy · FTK Imager · WinRAR · OpenPuff · Windows Registry Recovery  


---

### 🔵 Digital Forensics — Multi-Scenario Crime Investigation
Three-scenario practical forensic investigation covering different domains of digital forensics.

- **Scenario 1:** Raw file carving from disk image using hex editor — identified file signatures, extracted JPG/PDF/ZIP/WMV files by start and end offsets, repaired corrupted files
- **Scenario 2:** ZIP metadata verification using FTK Imager and manual hex analysis — confirmed created, modified, and accessed timestamps independently
- **Scenario 3:** Email forensics on .PST file — analysed email headers, identified unknown vs legitimate mail servers (WHOIS), investigated mobile device for web history and hidden media evidence

**Tools:** HxD Hex Editor · FTK Imager · Autopsy · WHOIS Lookup · mobile forensics  


---

### 🟠 Intrusion Detection & Prevention System Lab
Built a full virtual company network environment and simulated 5 real-world cyberattacks with detection and prevention.

**Network Setup:**
- pfSense firewall · Kali Linux attack machine · Windows Server Domain Controller
- Ubuntu vulnerable machine · Windows 10 victim · Suricata IDS/IPS · Wazuh SIEM

**Attacks Simulated & Detected:**
- DDoS / SYN Flood — detected via Suricata + Wireshark, blocked at firewall
- SSH Brute Force — detected via Wazuh alerts, IPS blocked attacker IP
- ARP Spoofing — detected via Suricata custom rules, network traffic analysis
- Reverse Shell — payload delivery via Metasploit, caught by IDS signatures
- Network Enumeration — Nmap/DNS enum detected, IPS blocking configured

**Tools:** Suricata · Wazuh · Wireshark · Metasploit · pfSense · Kali Linux · Windows Server  


---

### 🟡 Pareto Law Network Traffic Analyser
Designed and built a custom Python script applying the Pareto Principle (80/20 rule) to network log analysis across multiple operating systems.

- Analysed logs from CentOS, Windows 7 (32/64-bit), Windows XP, and Windows Vista
- Script automatically identifies the 20% of network nodes generating 80% of traffic
- Enables faster anomaly detection by focusing monitoring on high-impact sources
- Cross-platform log parsing with unified output for network administrators

**Tools:** Python · CentOS · Windows log analysis · network traffic parsing  

---

### 🟢 Network Configuration Lab — DHCP & Routing
Configured a multi-router network topology from scratch.

- Set up R2 as DHCP server with address pools for two subnets
- Configured R1 as DHCP relay agent using IP helper addresses
- Implemented RIPv2 dynamic routing across three routers
- Applied security hardening: encrypted passwords, login banners, SSH access

**Tools:** Cisco IOS · Packet Tracer · RIPv2 · DHCP · SSH  


---

### 🔨 Website Security Scanner SaaS *(In Progress)*
Building a web-based security scanner for OWASP Top 10 vulnerabilities with AI-powered reporting.

- Python + FastAPI backend
- Automated checks for SQLi, XSS, open redirects, misconfigured headers
- AI-powered vulnerability reporting (planned)
- SaaS model with free tier for small businesses



---

### 🤖 AI-Powered Forex Trading Bot *(In Progress)*
Building an automated EUR/USD trading bot using Python and machine learning.

- Data analysis of historical EUR/USD price data
- Signal generation using technical indicators
- Risk management module with stop-loss logic
- Backtesting framework to evaluate strategy performance



---

## 📚 Currently Learning

- Bug bounty hunting — HackerOne · Bugcrowd
- Advanced Python for security automation
- Data Structures & Algorithms (LeetCode daily)
- System Design fundamentals
- Chinese language (HSK preparation)

---

## 🏆 Goals

- [ ] First bug bounty submission on HackerOne
- [ ] Launch Website Security Scanner MVP
- [ ] Publish a cybersecurity research paper
- [ ] Secure a cybersecurity internship at a top company
- [ ] CompTIA Security+ certification

---

## 🤝 Open To

- Freelance cybersecurity consulting and security audits
- Bug bounty collaboration
- Research and paper writing opportunities
- Entry-level cybersecurity roles and internships

---

## 📬 Connect With Me

> LinkedIn · www.linkedin.com/in/danyal-hussain-a5700a241

---

*"Security is not a product, it's a process." — Bruce Schneier*
