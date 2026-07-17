# 📑 Cybersecurity Notes: Network Architecture & Models

This repository contains my professional study notes as a Software Engineering student transitioning into Cyber Security and Red Teaming. It covers the core foundations of network architecture, protocol layers, and data communication mechanisms.

---

## 🏛️ 1. OSI vs. TCP/IP Model (The Hacker's Perspective)

To attack or defend a network, you must understand the layers through which data travels. Networking is divided into two conceptual frameworks: **OSI (7 Layers)** and **TCP/IP (4 Layers)**.

### 🌐 The 7 Layers of the OSI Model

1. **Layer 7: Application** 
   * *What it does:* The interface between the user and the network (Protocols: HTTP, HTTPS, FTP, SSH, DNS).
   * *Red Team Context:* Web application hacking, phishing, and API exploitation happen at this layer.
2. **Layer 6: Presentation**
   * *What it does:* Data formatting, encryption, and compression (e.g., SSL/TLS, ASCII, JPEG).
3. **Layer 5: Session**
   * *What it does:* Establishes, manages, and terminates connections between local and remote applications.
4. **Layer 4: Transport**
   * *What it does:* Manages end-to-end communication, flow control, and error recovery (Protocols: TCP, UDP).
   * *Red Team Context:* Port scanning (Nmap) directly analyzes Layer 4 behavior to identify open services.
5. **Layer 3: Network**
   * *What it does:* Handles logical addressing and routing of packets across different networks (Protocols: IP, ICMP, ARP).
   * *Red Team Context:* IP spoofing and network reconnaissance (`ping`, `traceroute`) operate here.
6. **Layer 2: Data Link**
   * *What it does:* Handles physical addressing (MAC addresses) and frames data on the local network interface.
   * *Red Team Context:* Local network attacks like MAC Flooding, ARP Spoofing, and Wi-Fi cracking take place at L2.
7. **Layer 1: Physical**
   * *What it does:* The physical transmission of raw binary data (bits) over cables, fibers, or radio waves.
   * *Red Team Context:* Physical breach, rogue devices (e.g., Rubber Ducky, Hak5 devices), or wiretapping.

### 🌐 The 4 Layers of the TCP/IP Model
The real-world internet runs on the TCP/IP suite, which condenses the OSI model:
* **Application Layer** (Combines OSI L5, L6, L7)
* **Transport Layer** (Maps to OSI L4)
* **Internet Layer** (Maps to OSI L3)
* **Network Access Layer** (Combines OSI L1, L2)

---

## 🆔 2. MAC vs. IP Addressing (L2 & L3 Communication)

Network devices use two distinct types of addresses to communicate globally and locally:

### ⚙️ Physical Addressing: MAC Address (Layer 2)
* **Definition:** Media Access Control address. A unique 48-bit physical identifier burned into the Network Interface Card (NIC) by the manufacturer (e.g., `00:1A:2B:3C:4D:5E`).
* **Scope:** Only used for local communication inside the same local area network (LAN / Broadcast domain).
* **Security Risk:** Attackers can perform **MAC Spoofing** to bypass network access control (MAC Filtering) by mimicking a legitimate device's MAC.

### ⚙️ Logical Addressing: IP Address (Layer 3)
* **Definition:** Internet Protocol address. A logical identifier assigned dynamically or statically to device interfaces (e.g., IPv4: `192.168.1.5`).
* **Scope:** Used for routing data packets across globally interconnected networks (WAN / Internet).
* **Key Concept:** Routers strip away Layer 2 MAC headers and look at Layer 3 IP headers to forward data to the next destination.

---

## 🎯 Status: Module 1 Completed!

* **Topic:** Network Architecture, OSI & TCP/IP Models, L2/L3 Addressing Fundamentals.
* **Status:** 100% Completed & Reviewed.
* **Next Goal:** Deep dive into Protocol Internals (TCP, UDP, DNS, DHCP, ICMP).

---
🚀 *Successfully completed Topic 1. Ready to push to production.*
