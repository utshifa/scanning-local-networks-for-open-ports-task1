Task 01: Local network port scan

#Environment
**os: kali linux(VM)
**Nmap version: 7
**Date: 22 Sept 2025
**subnet scanned: 10.0.2.0/24

---

##Commands Used
- sudo nmap -sS your-ip-subnet -oN scans/scan.txt -oX scans/scan.xml
#to convery XML to HTML
- xsltproc /path/to/nmap.xsl scans/scan.xml > scans/scan.html

#Summary
ports found: 135, 445, 10000
tcp ports
state: open
 
