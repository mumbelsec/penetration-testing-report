# penetration-testing-report
Penetration testing report - Footprinting and Scanning Phase (NetworkWalks)

**W2-PM | Cyber Security | NetworkWalks**

| Field | Details |
|---|---|
| **Pentester Name** | Ibrahim Muhammed Bello |
| **Program/Batch** | BO83-Networkwalks |
| **Date** | 20 September, 2026 |
| **Modules Completed** | W2-PM1 (Multiple Kali Tools), W2-PM5 (Zenmap Scanning) |
| **Client/Target** | 1. Networkwalks<br>2. My own local LAN Network |
| **Permission Secured from Client?** | Yes |
| **Phases Covered** | Phase 1: Reconnaissance & Footprinting<br>Phase 2: Scanning & Network Discovery |

## 1. Liability Disclaimer

This assessment is strictly carried out within the scope authorized by the client.

## 2. Introduction

This report covers the footprinting of the NetworkWalks domain, using multiple Kali Linux tools, and also the scanning results of my local IP address using Zenmap. This report has two steps which show how attackers move from gathering information from public sources to mapping live hosts on a network. The footprinting was done using Linux, while the scanning was done using Zenmap installed on a Windows device.

## 3. Tools Used

| Tools | Purpose |
|---|---|
| Kali Linux & Windows | Operating systems used for reconnaissance activities. |
| whois | Find domain registration details (name, dates, servers). |
| whatweb | Fingerprint web technologies (server, CMS, plugins, IP). |
| nslookup | Resolve the domain name to its IP address using DNS. |
| curl -I | Read the HTTP response headers of the website. |
| wafw00f | Detect whether a Web Application Firewall protects the site. |
| dnsrecon -d | Enumerate all DNS records (NS, MX, SPF, TXT, and SRV). |
| Zenmap (Nmap GUI) | Scan the local subnet to find live hosts, IPs, and MAC addresses. |
| Windows cmd | Identification of local IP and MAC address. |
