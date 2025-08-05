# 🚨 Phase 6: Monitoring, Detection, and Response


cybersecurity internship Phase6. In this phase, I implemented end-to-end monitoring and threat detection across both endpoints and networks. I also conducted real-world attack simulations and developed a complete incident response and SOC strategy.

---

## 🛡️ Key Objectives

- ✅ Configure **Wazuh** for endpoint detection and response (EDR)
- ✅ Install and simulate **Sysmon** for enriched Windows logging
- ✅ Set up **Security Onion** with Suricata and Zeek for network-based detection
- ✅ Conduct **penetration testing** using Metasploit from Kali to Metasploitable2
- ✅ Generate and analyze alerts using Wazuh and Security Onion dashboards
- ✅ Develop a detailed **Incident Response Plan** and **SOC playbook**
- ✅ Document security metrics, detection coverage, and patching strategy

---

## 🧰 Tools and Technologies Used

| Tool              | Purpose                                           |
|-------------------|--------------------------------------------------|
| Wazuh             | Endpoint detection and log analysis              |
| Sysmon            | Windows telemetry and behavior monitoring        |
| Security Onion     | Network intrusion detection and alerting        |
| Suricata          | Signature-based network threat detection (NIDS) |
| Zeek              | Network traffic analysis and behavior monitoring |
| Kibana (SO)       | Alert and log visualization                      |
| Kali Linux        | Offensive security / Penetration testing         |
| Metasploit        | Exploitation framework used for simulations      |
| Ubuntu Linux      | Wazuh agent testing environment                  |
| Metasploitable2   | Vulnerable VM used as target                     |
| Nmap              | Network scanning tool                            |

---

## 📸 Screenshots (located in `sf_Pictures`)

- Wazuh dashboard with triggered alerts
- Security Onion Kibana alert view
- Metasploit console output
- Nmap scan simulation results
- Incident Response flow diagram 

---

## 🔬 Activities Performed

### 🔍 Endpoint Detection with Wazuh
- Installed and configured Wazuh agent on Ubuntu
- Simulated attacks using:
  - `curl` to malicious sites
  - `nmap` scans
  - User creation (`adduser hacker`)
- Verified rule triggers in Wazuh dashboard

### 🌐 Network Threat Detection with Security Onion
- Installed and configured SO VM with Suricata + Zeek
- Ran:
  - Nmap scans from Kali to SO
  - Metasploit exploits to Metasploitable2
- Detected and visualized alerts using Kibana and Hunt

### 💣 Penetration Testing with Metasploit
- Exploited vulnerable FTP service on Metasploitable2
- Observed detection in Security Onion
- Used this to validate IDS effectiveness

### 🧯 Incident Response & SOC Strategy
- Created a real-world incident response flow
- Defined SOC team roles (T1, T2 Analyst, Responder)
- Outlined containment, eradication, recovery steps
- Developed playbook for rapid action in case of alerts

### 📈 Security Metrics and Patch Management
- Documented alerts by severity and system
- Demonstrated system hardening via:
  - `sudo apt update && sudo apt upgrade`
- Measured detection and response effectiveness

---

## 📄 Final Report

The full documentation of this phase is available here:

👉 `Phase6_Monitoring_Response_Plan.pdf`

It includes:
- Executive summary
- Screenshots
- Tool configurations
- Detection results
- SOC plan
- Incident response workflow
- Lessons learned

---

## 🔗 Connect with Me

This GitHub project is part of my 6-phase cybersecurity internship. Feel free to view my previous phases and reach out on LinkedIn.

📂 [ Internship Phases on GitHub](https://github.com/rlinemavuyangwa?tab=repositories)  
🌐 [Connect on LinkedIn](https://www.linkedin.com/in/rlinemavuayangwa/)

---

