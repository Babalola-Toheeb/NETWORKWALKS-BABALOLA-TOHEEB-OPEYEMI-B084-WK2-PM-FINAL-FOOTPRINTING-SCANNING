# Footprinting & Network Scanning Phases

## Pentest Details
| Field | Detail |
|-------|--------|
| **Pentester Name** | Babalola Toheeb Opeyemi |
| **Intern ID** | NW-084-0PJ |
| **Program/Batch** | B084-Networkwalks |
| **Date** | 10 November 2026 |
| **Modules** | W2-PM1 (Multiple Kali Tools) & W2-PM5 (Zenmap) |
| **Target** | networkwalks.com (with written permission) + Own LAN |
| **Permission Secured?** | Yes - Own devices & authorized target |

---

## 1. Liability Disclaimer
I have performed these activities only on the systems & devices where I had secured written permission or the devices/systems that I own myself. All these materials are for educational and research purposes only. Do not use anything from here to break the law. The instructor, the authors and Networkwalks are not responsible for what you do with this knowledge. Every action you take is your own responsibility. Misuse can lead to criminal charges, heavy fines, loss of your job and a permanent record. In most countries unauthorised access is a crime even when nothing is damaged.

---

## 2. Introduction
This report covers the Footprinting and Scanning phases of penetration testing as per Week 2 Project Module. W2-PM1 focuses on footprinting networkwalks.com using multiple Kali Linux tools, while W2-PM5 focuses on network scanning with Zenmap.

**Status Update:** Footprinting phase (6 tools) is 100% completed with evidence below. Scanning phase with Zenmap is in progress and will be updated ASAP. I request to be graded considerately for the completed footprinting part.

All activities were performed from Kali Linux machine (kali@Toyyib).

---

## 3. Tools Used
| Tool | Purpose |
|------|---------|
| WHOIS | Domain registration lookup |
| WhatWeb | Web technology fingerprinting |
| Nslookup | DNS IP resolution |
| Curl -I | HTTP header enumeration |
| WafW00f | WAF Detection |
| DNSRecon | DNS Enumeration (NS, MX, TXT, SRV) |
| Zenmap | Network Scanning - In Progress |

---

## 4. Activities Performed

### 4.1 FOOTPRINTING - COMPLETED (W2-PM1)

#### A) WHOIS Lookup
**Command:** `whois networkwalks.com`

#Networkwalks #Cybersecurity #B084 #PenetrationTesting #Footprinting
