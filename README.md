<div align="center">

# Parth Doshi

> *"I take things apart to understand them."*

**Embedded & IoT Security Researcher · Hardware Hacker · Firmware Reversing**  
Electronics & Communication Engineering (AI & ML) @ MIT-WPU, Pune

[![Website](https://img.shields.io/badge/Portfolio-parthdoshi.me-0E0A06?style=flat-square&logo=google-chrome&logoColor=5FCE86)](https://parthdoshi.me)
[![Resume](https://img.shields.io/badge/Resume-1--Page%20PDF-0E0A06?style=flat-square&logo=adobeacrobatreader&logoColor=E9DFC9)](https://www.parthdoshi.me/Parth_Doshi_Resume.pdf)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-parthdoshi404-0a66c2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/parthdoshi404)
[![TryHackMe](https://img.shields.io/badge/TryHackMe-AlcesOzdst-212c42?style=flat-square&logo=tryhackme&logoColor=white)](https://tryhackme.com/p/AlcesOzdst)
[![Hack The Box](https://img.shields.io/badge/Hack%20The%20Box-AlcesOzdst-9fef00?style=flat-square&logo=hackthebox&logoColor=black)](https://profile.hackthebox.com/profile/019c59d7-edfc-7172-b666-bedfbe635e49)
[![Field Notes](https://img.shields.io/badge/Writing-Field%20Notes-5FCE86?style=flat-square&logo=substack&logoColor=0E0A06)](https://www.parthdoshi.me/blog)

</div>

---

### ⚡ About Me

I come at security from the **hardware side** — reading datasheets, soldering test points, tracing signals with a logic analyzer, and dumping flash chips to analyze the firmware behind them. My research lives at the intersection of embedded microcontrollers, radio interfaces, and defensive architecture.

- 🎓 **Undergrad**: Third-year Electronics & Communication Engineering (AI & ML) at **MIT-WPU, Pune** *(Expected Grad: 2028)*.
- 🛡️ **Leadership**: **President @ Hack-X**, MIT-WPU's campus cybersecurity club — orchestrating CTFs, offensive/defensive workshops, and hardware hacking sessions.
- 💼 **Experience**: Former **R&D Intern at PHN Technology**, building and testing embedded IoT prototypes and firmware attack surfaces.
- 🏆 **CTF & Competitions**: **2nd Runner-up at HackMITWPU'25** (Team PARAM); competed at NCIIPC-AICTE Pentathon, DEFCON Pune, CyberVault Connect, and Smart India Hackathon.
- 🎯 **Looking Ahead**: Actively seeking **Embedded / IoT / Firmware Security Internships (2026–2027)**.

---

### 🔬 Core Focus Areas

```
┌────────────────────────────────┐  ┌────────────────────────────────┐  ┌────────────────────────────────┐
│  ⚡ Firmware & Reversing        │  │  📡 Hardware & IoT Security    │  │  🛡️ Vulnerability Research     │
├────────────────────────────────┤  ├────────────────────────────────┤  ├────────────────────────────────┤
│ • Firmware extraction (Flash)  │  │ • UART, SPI, I²C, GPIO buses   │  │ • Responsible bug disclosures  │
│ • Static analysis with Ghidra  │  │ • RF (2.4GHz NRF24L01, LoRa)   │  │ • Access control flaws (IDOR)  │
│ • Binwalk & binary inspection  │  │ • Logic analyzer signal tracing│  │ • GraphQL & API reconnaissance │
│ • Register-level bare-metal C  │  │ • Device-to-cloud attack surface│  │ • Network traffic analysis     │
└────────────────────────────────┘  └────────────────────────────────┘  └────────────────────────────────┘
```

---

### 🛠️ Featured Projects & Security Research

| Project | Description | Stack / Focus | Link |
| :--- | :--- | :--- | :---: |
| **ESP32 Marauder Custom Suite** | Customized wireless security testing firmware incorporating NRF24L01 2.4 GHz transceivers, custom OLED UI navigation, and RF packet inspection. | `ESP32` `Embedded C++` `PlatformIO` `SPI` `RF` | [**Research**](https://parthdoshi.me) |
| **IoT DDoS Lab & ML Mitigation** | Authorized resilience lab simulating HTTP floods and Slowloris attacks with live telemetry, paired with an ML classifier analyzing raw PCAPs via tshark. | `Python` `tshark` `scikit-learn` `Node.js` `React` | [**Repository**](https://github.com/AlcesOzdst/IoT_DDoS_Lab) |
| **C8051 Bare-Metal Sensor Hub** | Register-level bare-metal firmware driving an SSD1306 OLED, ultrasonic, temperature, and PIR sensors on an 8-bit bus without external libraries. | `Bare-Metal C` `C8051F340` `I²C` `SPI` | [**Details**](https://parthdoshi.me) |
| **CTF Challenges & Solves** | Curated writeups, exploit scripts, and methodology across hardware, reverse engineering, web exploitation, and cryptography. | `Python` `Ghidra` `Burp Suite` `Cryptography` | [**Repository**](https://github.com/AlcesOzdst/CTF_Challenges) |
| **Smart Fire Prevention IoT** | Smart fire suppression system integrating ESP8266 IoT telemetry with an autonomous analog hardware failsafe (LM393 + logic gates) that operates even if the MCU halts. | `ESP8266` `C++` `IoT` `Hardware Failsafe` | [**Repository**](https://github.com/AlcesOzdst/Smart-Fire-Detection-IoT) |
| **thinkviz.tech** | Interactive AI algorithm visualization platform enabling students to explore algorithm mechanics and decision trees step-by-step. | `Next.js` `TypeScript` `Tailwind CSS` | [**Repository**](https://github.com/AlcesOzdst/thinkviz.tech) |

---

### 🎯 Security Disclosures & Milestones

- **Responsible Disclosure (University ERP IDOR)**: Identified and reported an Insecure Direct Object Reference (IDOR) flaw in the university ERP portal via student PRN parameter manipulation. Prepared a full CVSS v3.1 report and collaborated with administration to patch the vulnerability.
- **Bug Bounty Findings**: Uncovered and reported CORS misconfigurations, exposed admin panels leading to account takeovers, and GraphQL introspection vulnerabilities across target programs (Under Armour, Whatnot via HackerOne).
- **Team PARAM (HackMITWPU'25)**: Secured 2nd runner-up in a competitive 24-hour cybersecurity CTF track.

---

### 🧰 Technical Arsenal

<table>
  <tr>
    <td width="22%"><strong>Hardware & Buses</strong></td>
    <td>
      <code>ESP32</code> · <code>ESP8266</code> · <code>Raspberry Pi 5</code> · <code>C8051F340</code> · <code>NRF24L01 (2.4 GHz)</code> · <code>LoRa (SX1278)</code> · <code>Logic Analyzers</code> · <code>UART</code> · <code>SPI</code> · <code>I²C</code> · <code>GPIO</code> · <code>JTAG/SWD</code>
    </td>
  </tr>
  <tr>
    <td><strong>Firmware & Reversing</strong></td>
    <td>
      <code>Binwalk</code> · <code>Ghidra</code> · <code>PlatformIO</code> · <code>ESP-IDF</code> · <code>Register-Level C</code> · <code>GDB</code> · <code>Flashrom</code>
    </td>
  </tr>
  <tr>
    <td><strong>Offensive Security</strong></td>
    <td>
      <code>Burp Suite Professional</code> · <code>Wireshark</code> · <code>tshark</code> · <code>Nmap</code> · <code>Metasploit</code> · <code>ffuf</code> · <code>Gobuster</code> · <code>OWASP Top 10</code> · <code>Kali Linux</code>
    </td>
  </tr>
  <tr>
    <td><strong>Languages & Tools</strong></td>
    <td>
      <code>C</code> · <code>Embedded C++</code> · <code>Python</code> · <code>Bash</code> · <code>TypeScript</code> · <code>SQL</code> · <code>Solidity</code> · <code>Git</code> · <code>Docker</code> · <code>Linux</code>
    </td>
  </tr>
</table>

---

### 📊 GitHub Activity

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=AlcesOzdst&show_icons=true&bg_color=0E0A06&title_color=5FCE86&text_color=E9DFC9&icon_color=5FCE86&border_color=2A2218&hide_border=false&count_private=true" alt="Parth Doshi's GitHub Stats" height="165" />
  &nbsp;
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=AlcesOzdst&layout=compact&bg_color=0E0A06&title_color=5FCE86&text_color=E9DFC9&border_color=2A2218&hide_border=false" alt="Top Languages" height="165" />
</div>

---

### ☕ Off the Clock

When I'm not probing pins, reverse-engineering firmware, or working through CTFs:
- 🏃 **GPS Logging**: Long, slow runs with a GPX logger tracing Baner and Aundh.
- 🎧 **Audio Gear**: Chi-fi IEM enthusiast with an ever-expanding rotation.
- 🎙️ **Debating**: Collegiate debate — *taking apart an argument exercises the exact same muscle as taking apart a binary.*

---

### 📫 Reach Me

<p align="center">
  📍 Pune, Maharashtra, India &nbsp;·&nbsp;
  ✉️ <a href="mailto:parthdoshi404@gmail.com">parthdoshi404@gmail.com</a> &nbsp;·&nbsp;
  🌐 <a href="https://parthdoshi.me">parthdoshi.me</a> &nbsp;·&nbsp;
  📄 <a href="https://www.parthdoshi.me/Parth_Doshi_Resume.pdf">Resume PDF</a>
</p>
