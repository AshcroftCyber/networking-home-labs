# 🧪 Lab 1: Home Network Scan – Know Your Network

## 🔍 Objective
To identify active devices on my home network using `nmap` and practice interpreting basic scan results.

## 🧰 Tools Used
- Kali Linux (on VirtualBox)
- `nmap`
- Pocket WiFi (router)

## 📡 Steps Taken

1. Used `ip a` to find my device’s IP: `10.1.2.125`
2. Identified subnet: `/24` → full range `10.1.2.0 - 10.1.2.255`
3. Scanned the network with:
   ```bash
   sudo nmap -sP 10.1.2.0/24
4. Took a screenshot and copied a sample of the output.

## 🔍 Results Summary

- Over 30 live hosts found
- Devices include phones, laptops, unknown clients
- Pocket WiFi is shared or supports multiple connections

### 📄 Sample Scan Output

Nmap scan report for 10.1.2.1
Host is up (0.0021s latency).
Nmap scan report for 10.1.2.5
Host is up (0.00038s latency).
Nmap scan report for 10.1.2.15
Host is up (0.0021s latency).
Nmap scan report for 10.1.2.25
Host is up (0.00059s latency).
Nmap scan report for 10.1.2.30
Host is up (0.0185 latency).

*Note: Output trimmed for readability.*

## 💭 Reflection

This lab helped me understand basic network scanning, local IP ranges, and interpreting device behavior in shared WiFi environments. I’ll use this base knowledge in future deeper scans and packet analysis.

