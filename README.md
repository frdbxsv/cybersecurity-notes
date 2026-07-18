# 🛡️ Cybersecurity Notes

> Professional cybersecurity study notes documenting my journey from Software Engineering to Offensive Security and Red Teaming.

![Status](https://img.shields.io/badge/Status-Active-success)
![Focus](https://img.shields.io/badge/Focus-Cybersecurity-blue)
![Track](https://img.shields.io/badge/Track-Red%20Team-red)
![Language](https://img.shields.io/badge/Language-English-orange)

---

# 📖 About

Welcome!

This repository contains my structured cybersecurity study notes, practical explanations, and hands-on documentation.

Rather than simply completing courses, I document every topic I learn in a professional format while building a long-term knowledge base.

My primary focus areas include:

- Networking
- Linux
- Windows
- Active Directory
- Web Security
- Enumeration
- Privilege Escalation
- Red Team Methodology

---

# 🏛️ Module 01 - Network Architecture & Models

Understanding network architecture is one of the most important foundations in cybersecurity.

Every packet, request, and attack travels through multiple protocol layers. Learning these layers makes it easier to understand how attacks work and how defenders detect them.

---

## 🌐 OSI vs TCP/IP Model (The Hacker's Perspective)

Networking is commonly represented using two conceptual models:

- **OSI Model (7 Layers)** → Used for learning and troubleshooting.
- **TCP/IP Model (4 Layers)** → Used by the real Internet.

A security professional should understand both.

---

## 🖥️ OSI Model

### Layer 7 — Application

**Purpose**

Provides services directly to applications.

**Examples**

- HTTP
- HTTPS
- FTP
- SSH
- DNS

**Red Team Perspective**

- Web Application Testing
- API Exploitation
- Authentication Attacks
- Phishing

---

### Layer 6 — Presentation

**Purpose**

Responsible for:

- Encryption
- Compression
- Data Formatting

Examples include:

- SSL/TLS
- JPEG
- ASCII

---

### Layer 5 — Session

**Purpose**

Creates, manages and terminates communication sessions between hosts.

---

### Layer 4 — Transport

**Purpose**

Reliable or fast end-to-end communication.

Protocols:

- TCP
- UDP

**Red Team Perspective**

- Port Scanning
- Service Enumeration
- Banner Grabbing
- Network Renaissance

Common Tools:

- Nmap
- Netcat

---

### Layer 3 — Network

**Purpose**

Routes packets between networks.

Protocols:

- IP
- ICMP
- ARP

**Red Team Perspective**

- Ping Sweeps
- Traceroute
- IP Spoofing
- Routing Analysis

---

### Layer 2 — Data Link

**Purpose**

Uses MAC addresses for local communication.

**Red Team Perspective**

- ARP Spoofing
- MAC Spoofing
- MAC Flooding
- Wi-Fi Attacks

---

### Layer 1 — Physical

Responsible for transmitting raw bits.

Examples:

- Ethernet Cable
- Fiber
- Wireless Signals

**Red Team Perspective**

- Rogue Devices
- USB Attacks
- Rubber Ducky
- Physical Intrusion

---

# 🌍 TCP/IP Model

The Internet actually uses the TCP/IP protocol suite.

| TCP/IP | OSI Equivalent |
|---------|----------------|
| Application | L5 + L6 + L7 |
| Transport | L4 |
| Internet | L3 |
| Network Access | L1 + L2 |

---

# 🌐 MAC vs IP Address

## MAC Address (Layer 2)

**Definition**

A unique physical address assigned to every Network Interface Card (NIC).

Example:
