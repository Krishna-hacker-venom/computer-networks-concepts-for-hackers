# Networking Basics

## Q1. What is Networking?

**Definition:**
Networking refers to connecting two or more devices so they can communicate and share resources.

**Explanation:**
Networks are simply *things connected together*. These things can be computers, servers, mobile phones, printers, or any digital devices.

---

## Q2. What is the Internet?

**Definition:**
The Internet is a global network of networks.

**Explanation:**

* The Internet is one giant network that consists of many smaller networks connected together.
* The first version of the Internet started in the late 1960s as **ARPANET**, funded by the **United States Defense Department**.
* In **1989**, **Tim Berners-Lee** invented the **World Wide Web (WWW)**.
* After the creation of WWW, the Internet became a platform for storing, accessing, and sharing information globally.

### Types of Networks

A network can be of two types:

1. **Private Network** – Used inside organizations or homes.
2. **Public Network** – Accessible to anyone (example: the Internet).

---

## Q3. What is an IP Address?

**Definition:**
An IP (Internet Protocol) address is a unique identifier assigned to a device on a network.

**Explanation:**

* An IP address helps identify a **host** on a network for a specific period of time.
* The same IP address can later be assigned to another device.
* An IP address consists of **four octets** (for IPv4), separated by dots.
* Each octet is a number, and all four together form the device’s IP address.
* IP addressing is calculated using **IP addressing and subnetting techniques**.
* An IP address **cannot be used by two devices at the same time** in the same network.

### Types of IP Addresses

1. **Private IP Address** – Used inside local networks.
2. **Public IP Address** – Provided by the **Internet Service Provider (ISP)**, usually as part of your monthly internet bill.

### IPv6

IPv6 is the newer version of the Internet Protocol.

**Benefits of IPv6:**

* Supports **2¹²⁸ IP addresses** (around 340 trillion-plus)
* Solves the IP shortage problem of IPv4
* More efficient and secure due to improved methodologies

---

## Q4. Explain the Structure of a MAC Address

**Definition:**
A MAC (Media Access Control) address is a permanent, physical address assigned to a network interface card (NIC).

**Structure:**

* A MAC address is **48 bits long**
* Written in **hexadecimal format**
* Divided into **6 groups of 2 characters**

**Example:**

```
00:1A:2B:3C:4D:5E
```

**Explanation:**

* First 3 bytes: Manufacturer ID (OUI)
* Last 3 bytes: Unique device identifier
* MAC addresses are used at the **Data Link Layer** of the OSI model

---

## Q5. What is the Ping Command?

**Definition:**
The `ping` command is used to test connectivity between two devices on a network.

**Explanation:**

* It checks whether a host is reachable or not
* Uses **ICMP (Internet Control Message Protocol)**
* Measures **response time** between devices

**Example:**

```bash
ping google.com
```

**Uses of Ping:**

* Check network connectivity
* Troubleshoot network issues
* Measure network latency
