# 🛠️ Proxmox Cybersecurity Home Lab

This repository tracks the buildout of my personal cybersecurity lab using Proxmox VE. The goal is to simulate a real-world enterprise network environment for practicing detection engineering, blue team analysis, and threat response workflows.

## 🎯 Goals

- Deploy multiple virtual machines to simulate endpoints, servers, and attacker nodes
- Configure log generation and ingestion into a centralized SIEM (Security Onion or ELK)
- Practice log analysis, network monitoring, and threat detection
- Document every step for repeatability and reflection

## 📦 Planned VM Setup

| VM Name         | Purpose                      | OS           | Notes                         |
|------------------|-------------------------------|---------------|-------------------------------|
| `log-siem`       | Log aggregator + SIEM stack   | Ubuntu Server | Security Onion or ELK stack   |
| `workstation-1`  | Simulated endpoint            | Windows 10    | For attack simulation & logs  |
| `attacker-1`     | Attack simulation box         | Kali Linux    | Use for testing alerts        |
| `utility-nas`    | Shared storage / logging dump | Ubuntu Server | Optional shared NFS or SMB    |

## 🔧 Tools & Stack (Planned)

- **SIEM:** Security Onion, Zeek, Wazuh, Suricata
- **Network Tools:** Wireshark, tcpdump, netcat
- **Analysis:** Kibana, Logstash, Elasticsearch
- **Monitoring:** Sysmon, OSQuery, and custom scripts

## 📐 Topology Plan

Coming soon: network diagram + subnet plan

---

## 🧱 Additional Docs

- [💻 VM Plans](./vm_plans.md)
- [🧰 Tool Stack](./tools_list.md)


📅 **Project Timeline:** Ongoing  
✍️ Follow along as I document build steps, configs, and lessons learned.
