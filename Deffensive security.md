# 🛡️ Defensive Security – TryHackMe Pre Security Notes

## 🎯 What is Defensive Security?

Defensive security focuses on two core goals:

- 🔒 **Preventing intrusions** from happening.
- 🧠 **Detecting and responding** to intrusions when they do occur.

🔵 **Blue Teams** are responsible for these defensive efforts.

---

## 🛠️ Core Defensive Tasks

### 👩‍🏫 User Cyber Security Awareness
Training users to recognize cyber threats helps prevent attacks that exploit human error, such as phishing or social engineering.

### 🗃️ Documenting and Managing Assets
Understanding what systems and devices you have is crucial to protecting them.

### 🔄 Updating and Patching Systems
Ensure all computers, servers, and network devices are up-to-date and patched against known vulnerabilities.

### 🧱 Preventative Security Devices
- **Firewalls**: Control incoming and outgoing traffic.
- **IPS (Intrusion Prevention Systems)**: Block traffic based on signatures and behavior rules.

### 🧭 Logging and Monitoring
Properly configured logging and monitoring systems help detect suspicious activity. For example, spotting an unauthorized device on your network.

---

## 🏢 Security Operations Center (SOC)

A **SOC** is a dedicated team of cybersecurity professionals who monitor and respond to threats in real time.

### 🔍 Key Responsibilities of a SOC:

- **Vulnerabilities**: Monitor and coordinate the patching of discovered weaknesses.
- **Policy Violations**: Detect when users break internal security rules (e.g., uploading confidential data to public storage).
- **Unauthorized Activity**: Identify suspicious logins or use of stolen credentials.
- **Network Intrusions**: Rapidly detect and contain breaches due to phishing or server exploitation.

---

## 🧠 Threat Intelligence

**Threat Intelligence** is about gathering data on potential attackers to predict and prepare for threats.

### 🔐 Key Concepts:

- **Threat**: Any action that can harm or disrupt systems.
- **Adversaries**: These can vary depending on the industry (e.g., ransomware gangs, state-sponsored actors).

Examples:
- 🏦 A hacker group trying to steal customer data from a telecom provider.
- 🏭 A nation-state targeting a refinery to halt production.

### 🧪 Intelligence Process:

1. **Data Collection**: From internal logs and external sources like forums or breach data.
2. **Processing**: Format the data for analysis.
3. **Analysis**: Understand motives, techniques, and generate actionable insights.

🔁 Outcome: You build **threat-informed defense** and response strategies based on real adversary behavior.

---

## 🔍 Digital Forensics and Incident Response (DFIR)

DFIR includes:

- **Digital Forensics**
- **Incident Response**
- **Malware Analysis**

---

### 🧬 Digital Forensics

Forensics applies scientific methods to investigate cyber crimes and gather evidence.

#### 🔍 Key Focus Areas:

- **File Systems**: Discover deleted, overwritten, or installed files.
- **System Memory**: Analyze live memory for malware that doesn’t write to disk.
- **System Logs**: Reveal what actions took place, even if attempts were made to cover tracks.
- **Network Logs**: Understand how the attacker entered or moved through the network.

---

### 🚨 Incident Response

An **incident** can be a major breach or something small, like a misconfiguration.

#### ⚙️ Examples:
- Data breach
- Ransomware attack
- Unauthorized access
- Defacement of public websites

#### 🛠️ 4 Phases of Incident Response:

1. **Preparation**: Team is trained and tools are ready.
2. **Detection & Analysis**: Spot the incident and assess severity.
3. **Containment, Eradication, Recovery**:
   - Stop spread ➡ Clean system ➡ Recover operations.
4. **Post-Incident Activity**: Write a report, share lessons learned, improve for next time.

---

## ☠️ Malware Analysis

**Malware** = Malicious Software  
Types include:

- 🦠 **Virus**: Injects code into legitimate programs and spreads.
- 🐴 **Trojan Horse**: Appears useful but hides malicious functionality.
- 🔐 **Ransomware**: Encrypts files and demands payment to restore them.

### 🧪 Malware Analysis Methods:

- **Static Analysis**: Review malware code without running it.
  - Requires knowledge of **assembly language** and reverse engineering.
- **Dynamic Analysis**: Run the malware in a **controlled environment** to observe behavior.

---

By understanding **defensive security**, you learn how to **predict, detect, and respond** to threats before they cause damage — the backbone of a strong cyber defense team.

---

