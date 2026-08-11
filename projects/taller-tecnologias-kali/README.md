# Kali Linux Security Assessment Lab

University project focused on performing controlled security assessments and simulating common attack scenarios in an isolated virtual environment.

### Overview

I configured a **Kali Linux** virtual machine and used it to assess a second **Debian 12** machine through two controlled scenarios:

* Network reconnaissance and SSH password attacks
* Social engineering and phishing simulation

### Tools

* **Nmap** — used for host discovery, service enumeration, port scanning, and OS detection.
* **Hydra** — used to test SSH authentication against a controlled dictionary-based attack.
* **SET (Social-Engineer Toolkit)** — used to simulate a phishing scenario through website cloning.

### Technical Decisions

* Used **VirtualBox** to keep the entire assessment isolated from production systems.
* Configured Kali using **Bridged Networking** to allow direct communication with the target machine on the local network.
* Performed reconnaissance with **Nmap before attempting authentication attacks**, using the discovered SSH service as the entry point for the next phase.

### What I Learned

This project helped me understand that effective security testing starts with **reconnaissance and information gathering**, rather than immediately attempting exploitation. I also gained practical experience with common penetration-testing tools and learned how technical vulnerabilities and **human factors** can both become attack vectors.
