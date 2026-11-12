# WEEK 2 – CYBERSECURITY & ETHICAL HACKING INTERNSHIP

## 1. Student Details

- **Name:** Sanchita Hitesh Gandhi
- **Course:** B.Sc. Cyber Security – Third Year
- **College:** MES Abasaheb Garware College
- **Internship:** Networkwalks
- **Academic Year:** 2026–2027
- **Project:** Week 2

## 2. Introduction

This report documents the practical activities completed during Week 2 of my Cybersecurity and Ethical Hacking Internship.

The activities focused on footprinting, reconnaissance, information gathering and network scanning using different cybersecurity tools.

## 3. Objectives

- Understand the basics of footprinting and reconnaissance.
- Practise information gathering using cybersecurity tools.
- Identify website technologies and DNS information.
- Perform domain-based information gathering.
- Identify active hosts through network scanning.
- Understand network topology.

## 4. Tools Used

| Tool | Purpose |
|---|---|
| WHOIS | Domain registration information |
| WhatWeb | Website technology identification |
| Nslookup | DNS lookup |
| cURL | HTTP response headers |
| Wafw00f | WAF detection |
| DNSRecon | DNS reconnaissance |
| theHarvester | Email and subdomain gathering |
| Zenmap | Network scanning |

## 5. Practical Modules

### PM1 – Footprinting with Multiple Kali Linux Tools

**Target:** networkwalks.com

Six tools were used:

1. WHOIS – Collected domain registration information.
2. WhatWeb – Identified website technologies, including Apache and WordPress.
3. Nslookup – Performed domain name resolution.
4. cURL – Examined HTTP response headers.
5. Wafw00f – Detected ModSecurity (SpiderLabs) as the Web Application Firewall.
6. DNSRecon – Performed DNS record enumeration.

**Observation:** The website redirected HTTP requests to HTTPS. WhatWeb reported an HTTP 200 OK response for HTTPS.

**Evidence:** [View PM1 screenshots and outputs](PM1-Footprinting/)

### PM4 – Footprinting Using theHarvester

**Target:** microsoft.com

Two tasks were performed:

1. Information gathering using the Baidu source with a result limit of 1000.
2. Information gathering using all available sources with a result limit of 50.

The activity provided practical experience in domain-based information gathering and reconnaissance.

**Evidence:** [View PM4 screenshots and outputs](PM4-theHarvester/)

### PM5 – Network Scanning Using Zenmap

**Tool:** Zenmap (Nmap GUI)  
**Operating System:** Windows  
**Target Network:** 192.168.56.0/24

The following seven tasks were included in the practical:

1. Downloaded and installed Zenmap.
2. Checked local IP address and subnet using ipconfig.
3. Performed a Ping Scan to identify live hosts.
4. Identified the number of live hosts.
5. Examined the IP addresses of live hosts.
6. Examined the MAC addresses of live hosts.
7. Generated network topology and saved the output in PDF format.

**Scan Results:**

- Scan profile: Ping Scan
- Total IP addresses scanned: 256
- Live hosts detected: 1

The scan helped me understand host discovery and network visualization.

**Evidence:** [View PM5 screenshots and topology files](PM5-Zenmap/)

## 6. Learning Outcomes

- Learned domain footprinting and reconnaissance techniques.
- Practised using six Kali Linux tools.
- Understood website technology identification.
- Gained experience with theHarvester.
- Learned to perform network scanning using Zenmap.
- Understood how to identify live hosts.
- Learned to document practical findings and evidence.

## 7. Conclusion

The Week 2 internship activities provided practical exposure to important cybersecurity tools and techniques. These tasks improved my understanding of footprinting, information gathering, reconnaissance and network scanning.

The practical exercises also helped me improve my technical knowledge and confidence in using cybersecurity tools.

## 8. Project Evidence

All practical screenshots and text outputs are organised into separate folders:

- PM1-Footprinting
- PM4-theHarvester
- PM5-Zenmap

The folders contain the supporting evidence for the completed activities.

## 9. Ethical Considerations

All activities were performed for educational purposes as part of the internship. Network scanning and security testing should only be conducted on systems and networks where proper authorization is available.
