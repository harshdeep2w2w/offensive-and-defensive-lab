# Experiment 1 – Network Reconnaissance and Vulnerability Assessment using Nmap and Nessus

## Aim

To perform network reconnaissance and vulnerability assessment of a Metasploitable 2 vulnerable machine using Nmap and Nessus in a controlled cybersecurity laboratory environment.

---

## Lab Environment

| Component | Details |
|---|---|
| Attacker Machine | Kali Linux |
| Target Machine | Metasploitable 2 |
| Network | VMware Internal/Host-Only Network |
| Kali IP Address | 192.168.26.130 |
| Target IP Address | 192.168.26.129 |
| Tools Used | Nmap and Nessus |

---

# 1. Theory

## Nmap

Nmap (Network Mapper) is a network scanning and reconnaissance tool used to discover hosts, identify open ports, detect running services and determine operating system information.

Nmap provides different scanning techniques such as host discovery, TCP SYN scanning, service version detection and operating system detection.

## Nessus

Nessus is a vulnerability assessment tool used to identify vulnerabilities, security weaknesses and configuration problems in computer systems and networks.

It performs automated vulnerability scanning and classifies discovered vulnerabilities according to their severity.

---

# 2. Methodology

## Step 1 – Verify Network Connectivity

First, the connectivity between Kali Linux and the Metasploitable 2 machine was verified using the `ping` command.

### Command

```bash
ping -c 4 192.168.26.129
