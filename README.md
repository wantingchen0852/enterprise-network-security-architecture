# Enterprise Network Security Architecture & Automation

A hands-on enterprise security lab focused on **network segmentation, secure access, monitoring, and automated response**, designed to reflect real-world SOC and Network Security operations.

---

## 🔷 Network Architecture



**5 security zones were designed and enforced:**
- Outside (Untrusted Internet)
- DMZ (Public-facing services)
- Inside (User and staging systems)
- Interconnect (Firewall-to-firewall transit)
- Secure (Protected assets and monitoring)

**Goal:**  
Reduce attack surface and prevent lateral movement by enforcing strict zone isolation with enterprise firewalls.

---

## 🔐 Firewall Policy Enforcement (Palo Alto NGFW)



**What was configured:**
- Zone-based security policies
- NAT/PAT for outbound internet access
- Static NAT for limited DMZ exposure
- Explicit deny rules protecting the Secure zone

**Risk reduced:**  
Unauthorized access to sensitive systems and cross-zone lateral movement.

---

## 🌐 Secure Access & Zero Trust

**Implemented:**
- SSL/TLS Remote Access VPN
- Multi-Factor Authentication (Duo + RADIUS)
- Zero Trust Network Access using Guacamole

**Result:**  
Remote users can securely access internal resources **without exposing the internal network**.

---

## 🛡️ Detection, Monitoring & Automation

**Security monitoring stack:**
- Security Onion (IDS / Network Monitoring)
- Splunk SIEM (Log aggregation and analysis)

**Automation:**
- Docker + n8n workflows
- Automated firewall blocking based on SIEM alerts

**Outcome:**  
Reduced incident response from **manual multi-step actions** to an **automated response pipeline**.

---

## 📌 Key Skills Demonstrated

- Enterprise firewall configuration (Palo Alto, FortiGate)
- Network segmentation & defense-in-depth
- SIEM monitoring and alerting
- Security automation and incident response
- VPN, MFA, and Zero Trust principles
- Professional documentation and architecture design
