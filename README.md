# Security in Emerging Networks – Practical Assessment

This repository contains my practical cybersecurity assessment completed as part of my MSc Cyber Security studies.

The assessment explores web application security and network-level attacks through hands-on experiments in an isolated laboratory environment.

## Lab Tasks

### Task 1 – Cross-Site Scripting (XSS)

- Explored Stored XSS vulnerabilities in the Elgg application.
- Demonstrated JavaScript execution through an injected profile payload.
- Investigated session-based actions and self-propagating XSS worm behaviour.
- Observed how malicious scripts can affect other users' profiles.

### Task 2 – TCP RESET Attack

- Explored TCP connection establishment and communication.
- Established a Telnet connection between Docker containers.
- Used Wireshark/tcpdump concepts to observe TCP traffic.
- Implemented a TCP RESET attack using Python and Scapy.
- Examined how forged TCP RST packets can interrupt an active connection.

### Task 3 – DNS Cache Poisoning

- Explored DNS resolution and caching mechanisms.
- Studied the DNS cache poisoning attack process.
- Performed practical experiments in the provided laboratory environment.
- Investigated the security implications of manipulated DNS responses.

## Lab Environment

The practical exercises were performed using an isolated cybersecurity laboratory environment.

**Technologies and Tools:**
- Docker and Docker Compose
- Ubuntu Linux
- Kali Linux
- Python
- Scapy
- Telnet
- tcpdump
- Elgg vulnerable web application

## Repository Contents

- `README.md` – Project overview and lab information.
- `Security_in_Emerging_Networks_Assessment.pdf` – Final assessment report.

## Learning Outcomes

Through these practical exercises, I gained hands-on experience in:

- Understanding web application vulnerabilities.
- Analysing TCP communication and connection termination.
- Understanding packet crafting and network traffic analysis.
- Exploring DNS security and cache poisoning.
- Using Docker-based environments for cybersecurity experiments.

## Disclaimer

These experiments were conducted strictly for educational purposes within an authorised laboratory environment. The techniques demonstrated are intended for cybersecurity learning and defensive security awareness.

