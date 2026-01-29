## Project Overview

This project simulates a real-world **enterprise network security architecture** designed to protect sensitive systems while enabling secure public access and remote administration.

A **5-zone IPv4 network** (Outside, DMZ, Inside, Interconnect, Secure) was designed and deployed using **Palo Alto and FortiGate firewalls** to enforce strict segmentation, minimize attack surface, and prevent unauthorized lateral movement.

The environment includes **internet-facing DMZ services**, **secure internal systems**, and **centralized security monitoring**. Security controls such as **NAT/PAT, static NAT, SSL/TLS VPN, Multi-Factor Authentication (Duo + RADIUS)**, and **Zero Trust Network Access** were implemented to mirror modern enterprise security practices.

To enhance detection and response, **Security Onion and Splunk SIEM** were deployed to collect and analyze network and firewall logs. **Automation using Docker and n8n** was integrated to detect malicious activity and dynamically block offending IP addresses at the firewall, reducing manual incident response effort.

This project emphasizes **defense-in-depth**, **network segmentation**, and **security automation**, reflecting the responsibilities of real-world **SOC and Network Security Engineering** roles.
