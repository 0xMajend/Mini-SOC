# Implementation of a Security Operation Center (Mini-SOC) for SMEs

## 📌 Project Overview
This project was successfully developed and implemented as a **Graduation Project** by a collaborative team of 5 members. The primary objective was to design, deploy, and validate a cloud-based, scalable **Mini-SOC (Security Operations Center)** infrastructure hosted on **Vultr Cloud**. The system is tailored to provide small and medium-sized enterprises (SMEs) with centralized log management, continuous security monitoring, and proactive threat detection capabilities without enterprise-level budgets.

---

## 🚀 Key Features & Capabilities
* **Centralized Log Management:** Aggregates, correlates, and analyzes security events across the infrastructure in real-time.
* **Proactive Threat Detection:** Monitors host behavior and system-level changes to detect malicious activity early.
* **Network Defense & Isolation:** Implements strict traffic filtering and secure network segmentation.
* **Incident Response & GRC Alignment:** Mapped against the National Cybersecurity Authority compliance standards (**NCA ECC-2024**) and evaluated using industry KPIs (**MTTD & MTTR**).

---

## 🛠️ Tech Stack & Tools
The architecture leverages a robust set of open-source and cloud technologies:
* **SIEM Platform:** [Wazuh SIEM](https://wazuh.com/) (Centralized log collection, correlation, and alerting)
* **Endpoint Telemetry:** [Microsoft Sysmon](https://learn.microsoft.com/en-us/sysinternals/downloads/sysmon) (Advanced host-based monitoring for Windows/Linux)
* **Network Security:** [pfSense Firewall](https://www.pfsense.org/) (Traffic filtering, routing, and network isolation)
* **Cloud Infrastructure:** [Vultr Cloud](https://www.vultr.com/) (Virtual Private Cloud hosting)
* **Security Testing:** [Kali Linux](https://www.kali.org/) & [Nmap](https://nmap.org/) (Attack simulation and detection validation)

---

## 🏗️ Architecture & Methodology
1. **Infrastructure Deployment:** Provisioning a secure, isolated virtual environment on Vultr Cloud.
2. **Endpoint Monitoring:** Deploying Wazuh agents and tuning Sysmon configurations to capture high-fidelity process and network logs.
3. **Defense Validation:** Executing simulated cyber attacks (e.g., Brute-force, port scanning) using Kali Linux to test and refine **Incident Response Playbooks** and alerting thresholds.
4. **Compliance Mapping:** Ensuring all architectural controls align with the Essential Cybersecurity Controls (**NCA ECC-2024**).

---

## 👥 Team Members
This project was built and maintained by a dedicated team of 5 cybersecurity students:
* **Team Leader & Members** (يمكنك إضافة الأسماء هنا إذا رغبت)
