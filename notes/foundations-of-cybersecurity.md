# Foundations of Cybersecurity – Notes

## Module 1: Welcome to the World of Cybersecurity

### What Cybersecurity Is
- Cybersecurity = protecting devices, networks, data, and systems from digital attacks, damage, or unauthorized access.
- Focuses on the CIA Triad:
  - **Confidentiality**: Keeping data secret.
  - **Integrity**: Ensuring data is accurate and unaltered.
  - **Availability**: Making sure systems and data are accessible when needed.

### What Cybersecurity Professionals Do
- Monitor networks and systems for suspicious activity.
- Respond to incidents and contain threats.
- Assess vulnerabilities and apply patches.
- Develop and enforce security policies.
- Train users on safe practices.

### Skills Needed
- **Technical:** Networking, operating systems, scripting, SIEM tools.
- **Non-technical:** Communication, problem solving, critical thinking, teamwork.

### Entry-Level Roles
- SOC Analyst (Security Operations Center)
- Security Support Specialist
- Incident Response Technician
- Cyber Defense Analyst

---

## Module 2: The Evolution of Cybersecurity

### History
- Early attacks were mostly pranks or viruses.
- Modern attacks are complex, targeted, and often financially motivated.
- Growth of cloud, IoT, and connected devices expanded the attack surface.

### Common Attack Types
- **Phishing** – Fake messages trick users into revealing info.
- **Malware** – Malicious software like viruses, worms, ransomware.
- **DoS/DDoS** – Flooding systems with traffic to make them unavailable.
- **SQL Injection** – Inserting malicious queries into databases.
- **Man-in-the-Middle (MitM)** – Intercepting communication between two parties.

### Security Domains (High-Level)
- Risk Management
- Asset Security
- Security Engineering
- Communications & Network Security
- Identity & Access Management
- Security Assessment & Testing
- Security Operations
- Software Development Security

---

## Module 3: Threats, Risks, and Vulnerabilities

### Key Terms
- **Threat:** Potential cause of harm (e.g., malware, attacker).
- **Vulnerability:** A weakness that can be exploited.
- **Exploit:** The act of using a vulnerability.
- **Risk:** Likelihood a threat exploits a vulnerability and the impact it causes.

### CIA Triad
- **Confidentiality** – Protect data from unauthorized access.
- **Integrity** – Ensure data remains accurate and unchanged.
- **Availability** – Keep data and systems accessible when needed.

### Security Controls
- **Preventive:** Firewalls, access control, training.
- **Detective:** SIEM monitoring, IDS/IPS, logging.
- **Corrective:** Backups, patching, incident response.

### Frameworks & Principles
- **NIST Framework:** Identify, Protect, Detect, Respond, Recover.
- **Least Privilege:** Give users only the access they need.
- **Defense in Depth:** Use multiple layers of security.
- **Zero Trust:** Never trust by default, always verify.

### Ethics
- Always follow laws and respect privacy.
- Unauthorized testing or hacking is illegal without permission.

---

## Module 4: Cybersecurity Tools & Programming

### Common Tools
- **SIEM:** Splunk, Wazuh – collect and analyze logs for threats.
- **Network Analysis:** Wireshark, Nmap – scan and monitor network traffic.
- **Endpoint Security:** Antivirus, EDR – protect devices from malware and threats.

### Linux Basics
- Common commands: `ls`, `cd`, `pwd`, `cat`, `chmod`, `grep`
- Used for managing servers, analyzing logs, and automation.

### SQL Basics
- Used to query databases for anomalies and investigations.
- Example:  
  ```sql
  SELECT * FROM logs WHERE status='failed';
