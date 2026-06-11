<div align="center">

<img src="https://capsule-render.vercel.app/api?type=slice&color=0:0d1117,40:0a2a4a,100:1a6b8a&height=220&section=header&text=Hi,%20I%20am%20Garima%20Upadhyay.&fontSize=42&fontColor=ffffff&fontAlignY=55&fontAlign=50&desc=Aspiring%20Cybersecurity%20Professional%20%7C%20Secure%20Systems%20Developer%20%7C%20EC-Council%20Certified&descAlignY=75&descSize=14&descAlign=50" width="100%" />

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0A66C2)](https://www.linkedin.com/in/garimaupadhyayy)&nbsp;
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=181717)](https://github.com/garimaupadhyayy)&nbsp;
[![Gmail](https://img.shields.io/badge/Gmail-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=EA4335)](mailto:garima.upadhyay716@gmail.com)&nbsp;
![Profile Views](https://komarev.com/ghpvc/?username=garimaupadhyayy&style=for-the-badge&color=1a6b8a&label=PROFILE+VIEWS)

<br/>

</div>

---

## 🛡️ About Me

```js
const garima = {
  role:         "Cybersecurity Enthusiast & Secure Systems Developer",
  university:   "JECRC University, Jaipur  [2023–27]",
  year:         "Pre-Final Year  |  B.Tech CSE",
  cgpa:         7.73,
  focus:        ["Penetration Testing", "Threat Detection", "Incident Response"],
  interests:    ["Network Security", "AI + Security", "Cryptography", "OSINT"],
  certifiedBy:  ["EC-Council — CEH, CND, ECSS, CSCU", "Google Cybersecurity"],
  status:       "Open to Internships & Job Opportunities 🚀",
  funFact:      "I built a real HIDS that detects brute-force in under 6.4 seconds.",
};
```

I'm a **pre-final year Computer Science** undergraduate with hands-on experience in cybersecurity tools, threat analysis, and secure system development. Certified by **EC-Council** and **Google**. Passionate about building systems that actively **defend** — not just monitor.

---

## ⚔️ Tech Stack

### 💻 Languages & Core Programming
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

### 🔐 Cybersecurity & Penetration Testing
![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=for-the-badge&logo=kalilinux&logoColor=white)
![Metasploit](https://img.shields.io/badge/Metasploit-2596CD?style=for-the-badge&logo=metasploit&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white)
![Splunk](https://img.shields.io/badge/Splunk-000000?style=for-the-badge&logo=splunk&logoColor=white)
![VirusTotal](https://img.shields.io/badge/VirusTotal-394EFF?style=for-the-badge&logo=virustotal&logoColor=white)
![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=for-the-badge&logo=burpsuite&logoColor=white)
![VeraCrypt](https://img.shields.io/badge/VeraCrypt-Disk_Encryption-8B0000?style=for-the-badge&logo=gnupg&logoColor=white)

### 🌐 Networking & TCP/IP
![TCP/IP](https://img.shields.io/badge/TCP%2FIP-Protocol_Suite-0078D4?style=for-the-badge&logo=cisco&logoColor=white)
![tcpdump](https://img.shields.io/badge/tcpdump-Network_Analysis-333333?style=for-the-badge&logo=linux&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-Port_Scanner-4B0082?style=for-the-badge&logo=nmap&logoColor=white)

### 🖥️ Core Computer Science
![Data Structures](https://img.shields.io/badge/Data_Structures_%26_Algorithms-orange?style=for-the-badge&logo=leetcode&logoColor=white)
![OS](https://img.shields.io/badge/Operating_Systems-Linux%20%7C%20Windows-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Cryptography](https://img.shields.io/badge/Cryptography-SHA256%20%7C%20AES-6A0DAD?style=for-the-badge&logo=gnupg&logoColor=white)

### 🛠️ Tools & DevOps
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

---

## 🔐 Projects

> **Five builds. Each one solves a real security or systems problem.**

---

### 🔒 Host-Based Intrusion Detection System (HIDS)
> *"A machine that watches itself — so attackers can't hide."*

A fully Python-powered host-level intrusion detection system that monitors a machine from within — watching **authentication logs**, **file integrity**, **running processes**, and **active network connections** — and raises classified alerts in real time.

| Metric | Result |
|--------|--------|
| ⏱️ Scan Speed | Under **6.4 seconds** |
| ✅ Test Cases | **100% passed** |
| 💰 Cost to Deploy | **Zero** |
| 🖥️ Hardware Required | **None** (any standard laptop) |

**Key Features:**
- 🔑 SHA-256 file integrity monitoring with baseline comparison
- 🚨 Brute-force login detection via auth log parsing
- ⚙️ Suspicious process & unauthorized network activity detection
- 📊 Live cybersecurity dashboard — LOW / HIGH / CRITICAL severity
- 📧 Email alert notifications with real-time threat classification
- 🖼️ GUI built with Tkinter for interactive monitoring
- 🗂️ Logging system (`alerts.log`) + JSON baseline storage
- 🔐 Secure credential handling via `.env`

**Tech:** `Python` `Hashlib` `Tkinter` `Pandas` `Plotly` `Jupyter` `JSON` `Logging` `Threading`

---

### 📡 Real-Time File Integrity Monitoring & Alert System (FIM)
> *"Know the moment a file changes — before damage is done."*

A Python-based FIM system with GUI interface and email alert functionality. Monitors selected directories for file changes — Addition, Deletion, Modification — using SHA-256 hashing and generates real-time alerts.

**Key Features:**
- 🔍 SHA-256 hashing for tamper detection
- 📁 Directory monitoring every **10 seconds**
- ➕ Detects file addition, modification, deletion
- 📧 Email alert notifications on threats
- 🖼️ GUI built with Tkinter
- ⚙️ Multi-threaded execution for performance
- 🗂️ Baseline stored in JSON format
- 🔐 Secure `.env` credential handling

**Use Cases:** SOC environments · Threat detection systems · Incident response workflows

**Tech:** `Python` `Tkinter` `Hashlib` `JSON` `Logging` `smtplib` `Threading`

---

### 🌐 Network Monitoring & Traffic Analytics Dashboard
> *"See your network like a NOC engineer — in real time."*

A modern and interactive Network Monitoring & Traffic Analytics Dashboard built with HTML, CSS, and JavaScript. Provides real-time styled visualization of network traffic, bandwidth usage, alerts, connected devices, and system analytics through a responsive dark-themed dashboard UI.

**Key Features:**
- 📈 Real-time inspired network analytics dashboard
- 📊 Interactive charts and traffic visualization (Chart.js)
- 🚨 System alerts monitoring panel
- 📶 Bandwidth usage statistics
- 🖥️ Connected devices overview
- 🎨 Modern dark-themed professional UI
- 📱 Responsive and modular code structure

**Tech:** `HTML5` `CSS3` `JavaScript (ES6)` `Chart.js`

---

### 💬 Real-Time MultiClient Communication System
> *"A socket server that never drops a client."*

A socket-based real-time communication platform developed using Python that supports **multiple concurrent users** through TCP socket programming and multi-threaded server architecture.

**Key Features:**
- 👥 Multi-client support with concurrent connections
- 💬 Group messaging & private messaging
- 🟢 Online users list with live updates
- 📝 Chat logging for session history
- 🖼️ Tkinter GUI for client interface
- ⚙️ Multi-threaded server — one thread per client

**Tech:** `Python` `Socket Programming` `TCP/IP` `Threading` `Tkinter`

---

### 🔍 PortSentinel — TCP Port & Service Scanner
> *"Know what's exposed before the attacker does."*

A Python-based TCP port and service scanner capable of scanning ports **1–1024** to identify open ports and detect active services using real-time socket communication.

**Key Features:**
- 🔓 TCP port scanning across full 1–1024 range
- 🌐 Service identification: HTTP, FTP, SSH, HTTPS, and more
- ⚡ Fast socket-based scanning with structured output
- 🗺️ Network exposure analysis for basic reconnaissance
- 📋 Clear port-to-service mapping output

**Tech:** `Python` `Socket Programming` `TCP/IP` `Networking`

---

### 🎣 PhishTrace — Secure URL & Email Analyzer
> *"Catch phishing before it catches you."*

A rule-based phishing detection system to analyze URLs and email content using **10+ heuristic indicators** such as insecure protocols, suspicious keywords, and domain patterns.

**Key Features:**
- 🔗 URL Analysis: insecure protocols, IP-based URLs, suspicious structure
- 📧 Email Analysis: urgency language, suspicious links, phishing patterns
- 🎯 Risk scoring system (0–100) → Low / Medium / High classification
- 🧠 10+ heuristic rules for feature-based detection
- 📖 Transparent, explainable results per detection

**Tech:** `Python` `Regex` `Heuristic Analysis` `NLP Techniques`

---

## 💼 Work Experience

```
[Feb 2026 – Mar 2026]   Cyber Security Intern  @  ShadowFox  (Remote)
────────────────────────────────────────────────────────────────────
  ✓ Performed vulnerability assessment & network traffic analysis (Wireshark)
  ✓ Analyzed exposed services & monitored suspicious traffic patterns
  ✓ Identified potential security weaknesses in target systems
  ✓ Worked with Metasploit in controlled lab — pen testing & exploit simulation
  ✓ Documented findings in structured internship reports
```

---

## 🏆 Certifications

```
✓  Google Cybersecurity Professional Certificate       [Google]
✓  Google Project Management Professional Certificate  [Google]
✓  Certified Ethical Hacker (CEH)                     [EC-Council]
✓  Certified Network Defender (CND)                   [EC-Council]
✓  EC-Council Certified Security Specialist (ECSS)    [EC-Council]
✓  Certified Secure Computer User v3 (CSCU)           [EC-Council]
```

---

## 📊 GitHub Stats

<div align="center">

![Garima's GitHub Stats](https://github-readme-stats.vercel.app/api?username=garimaupadhyayy&show_icons=true&hide_border=true&bg_color=0d1117&title_color=1a6b8a&icon_color=1a6b8a&text_color=c9d1d9)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=garimaupadhyayy&layout=compact&hide_border=true&bg_color=0d1117&title_color=1a6b8a&text_color=c9d1d9)

![GitHub Streak](https://streak-stats.demolab.com?user=garimaupadhyayy&hide_border=true&background=0d1117&ring=1a6b8a&fire=1a6b8a&currStreakLabel=1a6b8a)

</div>

---

## 🌟 Leadership & Extras

```
→  Head of Administration  —  IAESTE LC JECRC  (2024–25)
   ✓ Managed 200+ international internship applications end-to-end
   ✓ Streamlined member onboarding, communication & cross-team coordination
   ✓ Official delegate at National Conference  —  MIT Manipal

→  Campus Ambassador  —  E-Cell IIT Bombay
   ✓ Increased student engagement in startup & entrepreneurship programs
```

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a6b8a,100:0d1117&height=100&section=footer" width="100%" />

*"Security is not a product. It's a process."*

</div>
