# WEEK 2 – CYBERSECURITY & ETHICAL HACKING INTERNSHIP REPORT

## 1. Student Information

- **Student Name:** Sanchita Hitesh Gandhi
- **Course:** B.Sc. Cyber Security – Third Year
- **College:** MES Abasaheb Garware College
- **Internship Organization:** Networkwalks
- **Project Week:** Week 2
- **Academic Year:** 2026–2027

## 2. Introduction

This report presents the practical activities completed during Week 2 of the Cybersecurity and Ethical Hacking Internship at Networkwalks.

The main focus of these activities was footprinting, information gathering, reconnaissance and network scanning. Different cybersecurity tools were used to understand how information about domains, websites and network devices can be collected and analysed.

## 3. Objectives

- To understand the fundamentals of footprinting and reconnaissance.
- To practise information gathering using cybersecurity tools.
- To identify website technologies and security mechanisms.
- To perform domain-based information gathering.
- To scan a network and identify active hosts.
- To document practical observations and results.

## 4. Tools and Technologies Used

| Tool | Purpose |
|---|---|
| WHOIS | Domain registration information |
| WhatWeb | Website technology identification |
| Nslookup | DNS information gathering |
| cURL | HTTP response and header analysis |
| Wafw00f | Web Application Firewall detection |
| DNSRecon | DNS reconnaissance |
| theHarvester | Email and subdomain information gathering |
| Zenmap | Network scanning and host discovery |

## 5. Practical Modules Completed

### PM1 – Footprinting with Multiple Tools

**Target Domain:** networkwalks.com

Footprinting was performed using six tools in Kali Linux.

The following activities were completed:

1. WHOIS – Collected domain registration details.
2. WhatWeb – Identified website technologies and server information.
3. Nslookup – Performed DNS lookup.
4. cURL – Examined HTTP response headers.
5. Wafw00f – Checked for Web Application Firewall detection.
6. DNSRecon – Performed DNS reconnaissance.

**Observations:**

- WHOIS provided domain registration information.
- WhatWeb identified Apache and WordPress-related technologies.
- The website redirected HTTP requests to HTTPS.
- The HTTPS request returned a 200 OK response.
- Wafw00f detected ModSecurity (SpiderLabs) protection.

The complete command outputs and screenshots are available in the PM1-Footprinting folder.

### PM4 – Information Gathering Using theHarvester

**Target Domain:** microsoft.com

The theHarvester tool was used to practise domain-based information gathering.

Two tasks were performed:

1. Information gathering using the Baidu source.
2. Information gathering using all available sources.

The activity provided practical exposure to collecting publicly available domain-related information.

The screenshots and command outputs are available in the PM4-theHarvester folder.

### PM5 – Network Scanning Using Zenmap

**Tool:** Zenmap (Nmap GUI)

**Target Network:** 192.168.56.0/24

Network scanning was performed using Zenmap to identify active hosts in the selected network.

**Scan Results:**

- Total IP addresses scanned: 256
- Live hosts identified: 1
- Scan type: Ping Scan

The scan results were examined using Zenmap. Network topology visualization was also performed as part of the practical activity.

The screenshots and topology evidence are available in the PM5-Zenmap folder.

## 6. Learning Outcomes

Through these practical activities, I gained knowledge of:

- Domain footprinting and reconnaissance.
- Using different tools for information gathering.
- Identifying website technologies and server details.
- Understanding DNS lookup and DNS reconnaissance.
- Detecting Web Application Firewall protection.
- Using theHarvester for domain information gathering.
- Performing network scanning using Zenmap.
- Analysing and documenting scan results.

## 7. Conclusion

The Week 2 internship activities provided practical exposure to important cybersecurity and ethical hacking tools. By completing the footprinting, information-gathering and network-scanning tasks, I developed a better understanding of reconnaissance techniques and their applications in cybersecurity.

These activities helped improve my technical knowledge and practical understanding of security assessment processes.

## 8. Project Evidence

The practical screenshots and output files are organised in the following folders:

- **PM1-Footprinting:** Screenshots and text outputs of six footprinting tools.
- **PM4-theHarvester:** Screenshots and text outputs of both information-gathering tasks.
- **PM5-Zenmap:** Network scan screenshots and topology evidence.

## 9. Ethical Considerations

All activities were performed for educational purposes as part of the internship. Information gathering and scanning should only be conducted on systems and networks where proper authorization is available.
