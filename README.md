# Task 01: Local Network Port Scan

## Overview
A basic **network scanner** on our local network to understand which devices and services are exposed. The goal was to identify **open ports** on devices in the network and assess potential security risks.

---

## Tools Used
- **Kali Linux (VM)** – operating system for running tools
- **Nmap** – network scanning tool
- **Wireshark** – for packet analysis 

---

## Steps Performed
1. Checked the VM’s IP address and identified the local network subnet.
2. Ran an Nmap **SYN scan (`-sS`)** on the subnet to detect open TCP ports.
3. Collected the scan results in **text (`scan.txt`)** and **XML (`scan.xml`)** formats.
4. Converted XML to **HTML report** for easier visualization.
5. Analyzed open ports and identified common services.
6. Documented findings and potential security risks in `report.md`.

---

## Outcome
- Learned how to perform a local network scan using Nmap.
- Understood which ports and services are commonly open on devices.
- Gained insight into potential security exposure of devices in a network.

---

## Files in this Repository
- `report.md` – detailed analysis and findings  
- `scans/` – contains raw scan outputs (`.txt`, `.xml`, `.html`)  
- `captures/` – packet captures for analysis(not included here)
