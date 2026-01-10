# 🧱 OSI Model – Layer-wise Protocols & Hacker Usage 

This document explains **each OSI layer**, the **commonly used protocols**, and **how hackers abuse or attack that layer**, in **simple language**.

---

## 🔼 Layer 7 – Application Layer

### 📘 What this layer does

* Direct interaction with the **user & applications**
* Provides network services to apps

### 🔧 Common Protocols

* HTTP / HTTPS
* FTP
* SMTP / POP3 / IMAP
* DNS
* SSH

### 🧑‍💻 How Hackers Use / Attack This Layer

* SQL Injection
* Cross-Site Scripting (XSS)
* Command Injection
* File Upload Attacks
* API Abuse
* Phishing (SMTP)

### 🎯 Example Attack

* Injecting SQL payload in a login form

---

## 🔼 Layer 6 – Presentation Layer

### 📘 What this layer does

* **Formats, encrypts, compresses** data
* Makes data readable for applications

### 🔧 Common Protocols / Standards

* SSL / TLS
* ASCII
* JPEG, MP3, PNG formats

### 🧑‍💻 How Hackers Use / Attack This Layer

* SSL Stripping
* Weak encryption exploitation
* Certificate spoofing
* Downgrade attacks

### 🎯 Example Attack

* Forcing HTTPS → HTTP to steal credentials

---

## 🔼 Layer 5 – Session Layer

### 📘 What this layer does

* Creates, manages, and terminates sessions
* Maintains communication state

### 🔧 Common Protocols

* NetBIOS Session Service
* RPC (Remote Procedure Call)
* PPTP

### 🧑‍💻 How Hackers Use / Attack This Layer

* Session Hijacking
* Session Fixation
* Cookie theft
* Replay attacks

### 🎯 Example Attack

* Stealing session cookies to bypass login

---

## 🔼 Layer 4 – Transport Layer

### 📘 What this layer does

* Ensures **reliable or fast delivery**
* Splits and reassembles data

### 🔧 Common Protocols

* TCP
* UDP

### 🧑‍💻 How Hackers Use / Attack This Layer

* Port Scanning (Nmap)
* SYN Flood (DoS)
* UDP Flooding
* TCP Reset attacks

### 🎯 Example Attack

* Flooding a server with TCP SYN packets

---

## 🔼 Layer 3 – Network Layer

### 📘 What this layer does

* Logical addressing & routing
* Chooses best path for packets

### 🔧 Common Protocols

* IP (IPv4 / IPv6)
* ICMP
* IPSec
* Routing protocols (OSPF, RIP, BGP)

### 🧑‍💻 How Hackers Use / Attack This Layer

* IP Spoofing
* ICMP Flood (Ping of Death)
* Route Injection
* Smurf Attacks

### 🎯 Example Attack

* Sending fake ICMP packets to crash a network

---

## 🔼 Layer 2 – Data Link Layer

### 📘 What this layer does

* Physical addressing (MAC)
* Error detection & frame delivery

### 🔧 Common Protocols

* Ethernet
* ARP
* PPP
* STP

### 🧑‍💻 How Hackers Use / Attack This Layer

* ARP Poisoning
* MAC Spoofing
* Man-in-the-Middle (MITM)
* Switch flooding

### 🎯 Example Attack

* Redirecting traffic using ARP spoofing

---

## 🔼 Layer 1 – Physical Layer

### 📘 What this layer does

* Transmits raw **bits (0s & 1s)**
* Handles hardware & signals

### 🔧 Common Technologies

* Ethernet cables
* Fiber optics
* Wi-Fi radio signals
* Hubs, NICs

### 🧑‍💻 How Hackers Use / Attack This Layer

* Cable tapping
* Hardware keyloggers
* Wi-Fi jamming
* USB drop attacks

### 🎯 Example Attack

* Plugging malicious USB to inject payload

---

## 🧠 Quick Hacker Memory Map

| OSI Layer | Focus      | Typical Attacks |
| --------- | ---------- | --------------- |
| 7         | Apps       | Injection, XSS  |
| 6         | Encryption | SSL attacks     |
| 5         | Sessions   | Hijacking       |
| 4         | Ports      | DoS, Scans      |
| 3         | IP         | Spoofing        |
| 2         | MAC        | ARP Poison      |
| 1         | Hardware   | Physical access |

---

## ✅ Final Note

Understanding **which protocol lives at which OSI layer** helps:

* Hackers choose **attack vectors**
* Defenders place **correct security controls**
* Students master **networking & cybersecurity basics**

---


