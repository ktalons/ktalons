<div align="center">

  <img src="https://github.com/user-attachments/assets/e4a940b9-8349-4d00-8bb0-f42dff2d029b" alt="Profile banner" />

  <h3>Kyle Versluis</h3>
  <p><strong>Cyber Operations – Engineering @ University of Arizona</strong> | <strong>OT/ICS SOC Analyst</strong> | <strong>CTF Captain</strong></p>

  <p>
    <a href="https://www.linkedin.com/in/ta1ons" target="_blank" rel="noopener noreferrer">
      <img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0077B5?logo=linkedin&logoColor=white" />
    </a>
    <a href="https://discord.com/users/1298401845366100049" target="_blank" rel="noopener noreferrer">
      <img alt="Discord" src="https://img.shields.io/badge/Discord-5865F2?logo=discord&logoColor=white" />
    </a>
    <a href="mailto:ktalonsec@gmail.com">
      <img alt="Email" src="https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white" />
    </a>
    <img alt="Profile views" src="https://komarev.com/ghpvc/?username=ktalons&label=Profile%20views&color=0e75b6&style=flat" />
  </p>

</div>

---

## About

I co-built an OT/ICS Security Operations Center from the ground up at the University of Arizona, designing the SIEM ingestion architecture, tuning detection logic, and triaging alerts across industrial control systems that serve the entire campus. Our SOC ingests **~2.5 million events per day** across **3 facility sites** using Elastic Stack — Suricata IDS, Zeek NSM, and custom ICS alert pipelines normalized to Elastic Common Schema (ECS).

- :mortar_board: Graduating **May 2026** — B.A.S. Cyber Operations (Cyber Engineering Emphasis)
- :shield: Student OT SOC Analyst & Engineer — University of Arizona Facilities Management (Apr 2025–Present)
- :jigsaw: CTF Captain, Cyber Saguaros — NCL Fall '25: Team 100/4,214 | MWCC 2026: Team 12th
- :closed_lock_with_key: CompTIA Security+ in progress (Expected April 2026)
- :robot: Interested in: security engineering, detection engineering, security automation, applied AI for cyber defense

---

## Technical Skills

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-121011?logo=gnu-bash&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?logo=c&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?logo=powershell&logoColor=white)

**Security & Detection**

![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?logo=elasticsearch&logoColor=white)
![Logstash](https://img.shields.io/badge/Logstash-005571?logo=logstash&logoColor=white)
![Kibana](https://img.shields.io/badge/Kibana-005571?logo=kibana&logoColor=white)
![Zeek](https://img.shields.io/badge/Zeek-5E5E5E?logoColor=white)
![Suricata](https://img.shields.io/badge/Suricata-DB3C30?logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?logo=wireshark&logoColor=white)
![Wazuh](https://img.shields.io/badge/Wazuh-3C3C3D?logoColor=white)
![Splunk](https://img.shields.io/badge/Splunk-000000?logo=splunk&logoColor=white)

**Platforms & Infrastructure**

![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Proxmox](https://img.shields.io/badge/Proxmox-E57000?logo=proxmox&logoColor=white)
![Active Directory](https://img.shields.io/badge/Active%20Directory-0078D4?logo=windows&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?logo=microsoftazure&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?logo=amazonaws&logoColor=FF9900)

**Ticketing & Threat Intel**

<sub>GLPI | osTicket | OpenCTI (threat intelligence) | MITRE ATT&CK</sub>

<sub><em>Exposure/roadmap: N8N, Ansible, Terraform, PostgreSQL, Moodle, KeyCloak, Vault</em></sub>

---

## Featured Projects

### CASA — Cybersecurity Analysis Support Agent
A modular AI agent supporting log and network traffic analysis for SME/MSP security operations. Guides investigative workflows with explainable reasoning aligned to NIST standards, with MITRE ATT&CK technique mapping across lateral movement, network beaconing, data exfiltration, and authentication anomaly workflows.
<br>**Repo:** [ktalons/casa-ai-agent](https://github.com/ktalons/casa-ai-agent)

### SOC Infrastructure & Tooling *(University of Arizona — [IAES-Repo](https://github.com/IAES-Repo))*
- **IAES Logstash Pipelines** — Modular multi-pipeline Logstash architecture for OT/ICS SIEM; normalizes Suricata IDS, Zeek NSM, and ICS alert logs to ECS. Processes ~2.5M events/day. *(Private; public redacted snapshot planned)*
- **DLQ Log Watcher & Manager** — Python automation for SIEM pipeline health monitoring and error-driven reingestion; detects Dead Letter Queue failures and triggers automated recovery. *(Private; public snapshot planned)*

### Security Tooling *(In Development)*
- **[PCAPpuller](https://github.com/ktalons/daPCAPpuller)** — Network forensics tooling — fast PCAP window selector, merger, and cleaner for high-volume packet collections. *(Active development)*
- **[bashedlogs](https://github.com/ktalons/bashedlogs)** — CLI tool for cybersecurity log analysis with automatic format detection. *(Active development)*
- **[Violent-Python](https://github.com/ktalons/Violent-Python)** — Curated collection of Python security scripting projects. *(Private)*

### Infrastructure & Administration
- **[Active Directory Lab](https://github.com/ktalons/ad-config)** — AD domain services deployment and configuration in Azure VMs for security testing and administration.
- **[osTicket](https://github.com/ktalons/osticket-install/)** — Help desk ticketing system: [Install](https://github.com/ktalons/osticket-install/) | [Configuration](https://github.com/ktalons/osticket-config) | [Ticket Lifecycle](https://github.com/ktalons/osticket-ticketdemo)

### Community Tools
- **[Cybersec Discord Bot](https://github.com/ktalons/cybersec-discord-bot)** — Discord bot for cybersecurity clubs — email verification, CTFtime integration, roster management, and event coordination. Used by the Cyber Saguaros community.

### Academic
- **THREADS** — Educational OS simulator (Spring 2025 OS Security Theory). Thread-safe producer-consumer queue, custom memory management, priority-based FIFO schedulers, synchronization primitives in C. [User Manual (PDF)](https://github.com/user-attachments/files/21332721/THREADS.User.Manual.v1.0.pdf)

---

## Certifications & Achievements

- :closed_lock_with_key: **CompTIA Security+** — In Progress (Expected April 2026)
- :shield: **Google Cybersecurity Professional** — [Coursera Certificate](https://www.coursera.org/account/accomplishments/professional-cert/NJDO3PFJSAQE) (Sep 2025)
- :robot: **Vanderbilt: Generative AI Cybersecurity and Privacy for Leaders** — Coursera (Nov 2025)
- :trophy: **NCL Fall 2025** — Team 100/4,214 | Individual 447/7,875 | [Verify](https://cyberskyline.com/verify/)
- :mountain: **Mountain West Cyber Challenge 2026** — Team 12th Place
- :scroll: **Dean's List** — Fall '25, [Spring '25](https://github.com/user-attachments/assets/733473a5-c95c-4e97-a689-6b13d0b2240d), [Fall '24](https://github.com/user-attachments/assets/44640182-5ffa-460b-ace2-225da6b5acec)
- :lock: **TryHackMe** — [Advent of Cyber 2024](https://tryhackme-certificates.s3-eu-west-1.amazonaws.com/THM-4WCS17MVTC.pdf) | [Pre-Security](https://tryhackme-certificates.s3-eu-west-1.amazonaws.com/THM-3TPPMDQU0G.pdf)

<img src="https://tryhackme-badges.s3.amazonaws.com/talons.png" alt="TryHackMe Badge" />

---

## Upcoming Competitions

- **NCAE Cyber Games** — Mar 7, 2026
- **MITRE 2026 eCTF** — Jan 14 – Apr 15, 2026
- **NCL Spring 2026**
- **picoCTF 2026**

---

## Leadership & Community

**CTF Captain** — Cyber Saguaros Club, University of Arizona (Mar 2025–Present)
<br>Lead teams of 4–8 across defensive and offensive CTF competitions. Run training sessions on incident response, detection engineering, and adversary tradecraft using MITRE ATT&CK.

**Cyber Range Volunteer** — [Saguaros CyberHub](https://github.com/ktalons/Saguaros-CyberHub) (Apr 2025–Present)
<br>Support Proxmox VM deployments, secure network segmentation, and firewall rule testing for training scenarios.

**Arizona Cybersecurity Clinic** — Engineering Team, Senior Capstone (Spring 2026)
<br>Conduct risk and vulnerability assessments; deliver actionable security recommendations for community partners. Capstone project: [PTS (Project Twilight Synapse)](https://github.com/Capstone-AI-Research-Project) — multi-agent AI-assisted cybersecurity analysis platform.

[Join the Cyber Saguaros Discord](https://discord.gg/bASJPxvKMw)

---

## Contact

Open to connecting about security engineering, detection architecture, OT/ICS security, CTF strategy, or AI for cyber defense.

<p>
  <a href="https://www.linkedin.com/in/ta1ons"><strong>LinkedIn</strong></a> &nbsp;|&nbsp;
  <a href="mailto:ktalonsec@gmail.com"><strong>Email</strong></a> &nbsp;|&nbsp;
  <a href="https://discord.com/users/1298401845366100049"><strong>Discord</strong></a>
</p>
