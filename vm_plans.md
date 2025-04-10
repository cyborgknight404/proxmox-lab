# 💻 VM Deployment Plan

This file outlines the virtual machines (VMs) planned for my Proxmox-based cybersecurity lab. Each VM will serve a specific purpose in simulating a real-world blue team/defensive security environment.

## 🧱 Core VMs

### `log-siem`
- **Purpose**: Centralized SIEM (Security Information and Event Management)
- **OS**: Ubuntu Server 22.04
- **Stack**: Security Onion (Zeek, Wazuh, Suricata, Kibana)
- **Role**: Ingest logs from all other VMs, provide dashboards, alerts, and analytics

### `workstation-1`
- **Purpose**: Simulated end-user system
- **OS**: Windows 10
- **Software**: Sysmon, OSQuery, random browsing/emulation scripts
- **Role**: Serve as a normal endpoint to generate real user-like telemetry

### `attacker-1`
- **Purpose**: Penetration tester/red team box
- **OS**: Kali Linux
- **Tools**: Metasploit, nmap, Hydra, password lists, exploits
- **Role**: Launch internal attacks to test detection and response

### `utility-nas`
- **Purpose**: File share/NAS/log dump
- **OS**: Ubuntu Server
- **Tools**: NFS/SMB server, rsyslog relay
- **Role**: Optional logging and file dump zone, backup test location

---

## 🔗 Network Plan (coming soon in `network_map.png`)
