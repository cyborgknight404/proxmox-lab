# 🧰 Tools and Stack

This is a running list of tools I'm using or planning to install in the Proxmox cybersecurity home lab.

---

## 🔍 SIEM & Log Collection

| Tool           | Use Case                          | VM              |
|----------------|-----------------------------------|------------------|
| Security Onion | Full-stack SIEM (Zeek, Wazuh, Kibana) | `log-siem`   |
| Zeek           | Network monitoring                | `log-siem`       |
| Suricata       | IDS/IPS engine                    | `log-siem`       |
| Wazuh          | Host-based intrusion detection    | `log-siem`, `workstation-1` |
| Sysmon         | Windows event logging             | `workstation-1`  |
| OSQuery        | Endpoint monitoring/querying      | `workstation-1`  |

---

## 📊 Visualization & Analysis

- **Kibana** – SIEM dashboards
- **Grafana (optional)** – Custom dashboards for log trends
- **ElasticSearch** – Data search backend
- **Logstash** – Log parsing and transformation

---

## 🛠 Offensive Testing Tools

- **nmap** – Network scanning
- **Metasploit** – Exploitation framework
- **Hydra** – Brute-force testing
- **Responder** – LLMNR/NBT-NS poisoning

---

## 📡 Utilities

- `tcpdump`, `netcat`, `htop`, `iftop`
- Bash + Python scripting
- Optional: Docker + Portainer for isolated tools

---

✅ This list will evolve as I test integrations, configs, and new use cases.
