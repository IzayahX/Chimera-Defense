# Chimera-Defense
A distributed honeypot and deception-based security system built from scratch on a Raspberry Pi cluster. This system is designed to proactively detect, analyze, and contain malicious network activity by luring attackers into a highly monitored, sandboxed environment of decoy services.



# 🎯 Project Purpose
Traditional cybersecurity defenses are primarily reactive, often detecting attacks only after a compromise has occurred. These methods struggle against advanced persistent threats, zero-day exploits, and sophisticated social engineering , leaving organizations with insufficient early warning systems.

This project's solution is a proactive, deception-based system. It provides early threat detection by deploying strategically-positioned decoy services that simulate legitimate, vulnerable network resources. By analyzing attacker behavior within this controlled environment, we can develop robust, real-time alerts and gather detailed forensic data —all without impacting legitimate services.

# ✨ Core Features

Distributed Deception Grid: Deploys four distinct honeypot nodes simulating a variety of common enterprise applications and vulnerable services (e.g., web applications, file servers).

Automated Traffic Redirection: Features a functional traffic containment system to automatically redirect suspicious activity to the honeypot infrastructure.

Real-Time Monitoring & Alerting: A centralized dashboard provides real-time activity monitoring and behavioral analysis. The system is capable of multi-channel notifications (email, SMS, dashboard) with a target latency of sub-60 seconds.

Forensic Analysis: Implements comprehensive logging, session recording, and artifact collection to document and categorize a minimum of 10 distinct attack methodologies.

# 🛠️ Tech Stack & Hardware

Hardware: 4x Raspberry Pi 4 Model B (8GB) Nodes 

Networking: 1x TP-Link 8-port Managed Switch 

OS: Raspberry Pi OS Lite (64-bit)

Core (Planned): Custom-built services (Python), iptables/ufw for traffic control, dnsmasq for network services, and a web-based dashboard for the management interface.

# 📈 Project Status

In Progress: Phase 2 - Development 

Currently building the foundational hardware and network infrastructure. Next steps include base honeypot service deployment and configuration.
