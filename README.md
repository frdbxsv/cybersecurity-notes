# 🛡️ Cybersecurity Notes

> Professional cybersecurity study notes documenting my journey from
> Software Engineering to Offensive Security and Red Teaming.

![Status](https://img.shields.io/badge/Status-Active-success)
![Focus](https://img.shields.io/badge/Focus-Cybersecurity-blue)
![Track](https://img.shields.io/badge/Track-Red%20Team-red)
![Language](https://img.shields.io/badge/Language-English-orange)

------------------------------------------------------------------------

## 📑 Table of Contents

-   About
-   Goals
-   Lab Environment
-   Learning Roadmap
-   Repository Structure
-   Module 01
-   Useful Commands
-   References
-   Progress
-   Next Module

------------------------------------------------------------------------

# 📖 About

This repository documents my cybersecurity learning journey through
structured notes, practical explanations, and hands-on labs. Every
module is written as a long-term knowledge base focused on Offensive
Security and Red Teaming.

## 🎯 Goals

-   Build a professional cybersecurity knowledge base.
-   Document every concept I learn.
-   Practice through labs and CTFs.
-   Develop Python & Bash tools.
-   Prepare for real-world Red Team work.

## 🧪 Lab Environment

  Category    Tools
  ----------- -------------------------
  OS          Kali Linux, Windows
  Platforms   TryHackMe, Hack The Box
  Network     Wireshark, Nmap
  Web         Burp Suite
  Scripting   Python, Bash

## 📂 Repository Structure

``` text
Cybersecurity-Notes/
├── 01-Networking/
├── 02-Protocols/
├── 03-Linux/
├── 04-Windows/
├── 05-ActiveDirectory/
├── 06-WebSecurity/
├── 07-Enumeration/
├── 08-BurpSuite/
├── 09-PrivilegeEscalation/
└── 10-CTF-Writeups/
```

## 📊 Learning Roadmap

  Module                 Status
  ---------------------- ----------------
  Networking             ✅ Completed
  Protocols              🚧 In Progress
  Linux                  ⏳ Planned
  Windows                ⏳ Planned
  Active Directory       ⏳ Planned
  Web Security           ⏳ Planned
  Enumeration            ⏳ Planned
  Burp Suite             ⏳ Planned
  Privilege Escalation   ⏳ Planned
  AD Attacks             ⏳ Planned
  CTF Writeups           ⏳ Planned

# 🏛️ Module 01 -- Network Architecture & Models

Understanding network architecture is one of the most important
foundations in cybersecurity.

## 🌐 OSI vs TCP/IP

OSI contains seven conceptual layers while TCP/IP is the practical model
used by modern networks.

### Layer 7 -- Application

Protocols: HTTP, HTTPS, FTP, SSH, DNS

**Red Team Perspective** - Web Application Testing - API Exploitation -
Authentication Attacks - Phishing

### Layer 6 -- Presentation

Responsible for encryption, compression and formatting.

### Layer 5 -- Session

Creates and manages communication sessions.

### Layer 4 -- Transport

Protocols: TCP, UDP

**Red Team Perspective** - Port Scanning - Banner Grabbing - Service
Enumeration

### Layer 3 -- Network

Protocols: IP, ICMP, ARP

**Red Team Perspective** - Ping Sweeps - IP Spoofing - Routing Analysis

### Layer 2 -- Data Link

Uses MAC addresses.

**Red Team Perspective** - ARP Spoofing - MAC Spoofing - MAC Flooding

### Layer 1 -- Physical

Physical transmission medium.

## 🌍 MAC vs IP

### MAC Address

Unique hardware identifier used within a LAN.

Example:

``` text
00:1A:2B:3C:4D:5E
```

### IP Address

Logical address used for routing.

Example:

``` text
192.168.1.25
```

## 🛠️ Useful Commands

``` bash
ipconfig
ifconfig
ping
arp -a
route print
tracert
traceroute
nslookup
netstat -ano
ss -tuln
```

## 📚 References

-   Cisco CCNA
-   TryHackMe
-   Hack The Box Academy
-   PortSwigger Academy
-   RFC 791
-   RFC 793
-   RFC 768
-   RFC 1035

## 📈 Progress

Networking ██████████ 100%

Protocols ██░░░░░░░░ 20%

Linux ░░░░░░░░░░ 0%

Windows ░░░░░░░░░░ 0%

## 📌 Disclaimer

These notes are for educational purposes and are continuously updated as
I learn new topics and complete practical labs.

## 🚀 Next Module

-   TCP
-   UDP
-   DNS
-   DHCP
-   HTTP
-   HTTPS
-   ICMP
-   ARP

> "Understanding how systems work is the first step toward understanding
> how they can be secured."


bele bir sey var mende bax bunu indi paylasmaq duzgun olar yoxsa gelecekde?
