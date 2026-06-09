# Hi, I'm Elvis Mbugua 👋
### Cloud Security Engineer (AWS) · I secure what I build

<a href="https://www.linkedin.com/in/elvis-mbugua-89b177331/"><img src="https://img.shields.io/badge/-LinkedIn-0072b1?&style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="https://3lv15p4ck3t.netlify.app/"><img src="https://img.shields.io/badge/-Portfolio-0B5468?&style=for-the-badge&logo=netlify&logoColor=white" /></a>

Software developer turned cloud security engineer, based in Nairobi 🇰🇪. I design and harden secure AWS environments — least-privilege IAM, infrastructure-as-code, and automated guardrails — and because I came up through engineering, I fix problems in code instead of just flagging them. I also think like an attacker: I pentest the web and API surfaces I defend.

- 🎓 **[Your Degree], KCA University**
- 🛡️ Trained across the full security lifecycle through **AfricaHackon Academy**
- 🔭 **Focus:** AWS security · IAM · Terraform / IaC security · policy-as-code
- ⚔️ **Offensive edge:** web & API penetration testing (OWASP Top 10, Burp Suite)
- ✍️ I document real cloud misconfigurations — the attack first, then the code that closes it

## 🧭 What I do
- **Build secure by default** — least-privilege IAM, hardened Terraform / CloudFormation, encryption everywhere, centralised logging baselines
- **Automate the defense** — IaC security scanning in CI/CD, policy-as-code, and auto-remediation with Python + Lambda
- **Detect & respond** — cloud logging, log analysis, and incident response (my blue-team foundation)
- **Attack to validate** — web & API pentesting to prove the hardening holds against real attack paths

## 🛠️ Projects & Writeups
| Project | What it covers |
|---------|----------------|
| ☁️ [**flaws.cloud — AWS Misconfiguration Walkthrough (Levels 1–6)**](assets/flaws-cloud-walkthrough.pdf) | Exploited public S3 buckets, global `AuthenticatedUsers` ACLs, AWS keys in Git history, an unencrypted public EBS snapshot, IMDSv1 metadata SSRF, and read-only IAM enumeration → Lambda invocation — each finding paired with the AWS control that closes it |
| ⚔️ [**Reconnaissance & Subdomain Enumeration**](assets/recon-subdomain-enumeration.pdf) | Passive + active subdomain discovery (Subfinder, Dnsenum), deduplicated with Anew, liveness-checked with httpx, and WAF-fingerprinted with wafw00f — scripted end to end, narrowing dozens of hosts down to the live, in-scope attack surface |
| ⚔️ [**Wireless Network Auditing & Pentesting**](assets/wireless-network-pentest.pdf) | Full WiFi attack chain in a virtualized 802.11 lab — monitor mode, rogue AP, deauth flood, WPA/TKIP handshake capture, and an aircrack-ng dictionary attack with rockyou |
| ⚔️ [**Windows Exploitation — Metasploit + ngrok**](assets/windows-exploitation-metasploit.pdf) | Exposed a Metasploit listener through an ngrok TCP tunnel, delivered a `reverse_http` Meterpreter payload to a Windows 10 VM, landed a live session, and ran post-exploitation enumeration — isolated lab only |
| 🎯 [**Financial-Sector Threat Model & Adversary Analysis**](assets/threat-model-financial-sector.pdf) | Direct & indirect targeting factors, supply-chain pivot paths, ranked adversary classes, and capability / timeframe assessment for a Kenyan asset-management firm |
| 🧱 [**Student Records — PHP + MySQL CRUD App**](assets/student-records-crud.pdf) | Full create / read / update / delete over MySQL using PHP PDO with prepared statements, results rendered in a Bootstrap table |

<!-- Add these as you build them:
| IaC Security Pipeline — Terraform scanning + auto-remediation | [repo](#) |
| Detection Lab — cloud logging, detection & incident response | [repo](#) |
| SOC Automation Lab — SOAR playbooks & case management | [repo](#) |
-->

## 🧰 Tools

**Cloud & Infrastructure-as-Code**
<div>
    <img src="https://img.shields.io/badge/-Amazon_AWS-232F3E?&style=for-the-badge&logo=amazon-aws&logoColor=white" />
    <img src="https://img.shields.io/badge/-Terraform-7B42BC?&style=for-the-badge&logo=terraform&logoColor=white" />
    <img src="https://img.shields.io/badge/-Linux-FCC624?&style=for-the-badge&logo=linux&logoColor=black" />
</div>

**Scripting & Automation**
<div>
    <img src="https://img.shields.io/badge/-Python-3776AB?&style=for-the-badge&logo=python&logoColor=white" />
    <img src="https://img.shields.io/badge/-Bash-4EAA25?&style=for-the-badge&logo=gnu-bash&logoColor=white" />
    <img src="https://img.shields.io/badge/-Git-F05032?&style=for-the-badge&logo=git&logoColor=white" />
</div>

**Offensive (Web / API)**
<div>
    <img src="https://img.shields.io/badge/-Burp_Suite-FF6633?&style=for-the-badge&logo=burpsuite&logoColor=white" />
    <img src="https://img.shields.io/badge/-Nmap-4682B4?&style=for-the-badge&logoColor=white" />
    <img src="https://img.shields.io/badge/-Metasploit-2596CD?&style=for-the-badge&logo=metasploit&logoColor=white" />
</div>

**Network & Detection**
<div>
    <img src="https://img.shields.io/badge/-Wireshark-1679A7?&style=for-the-badge&logo=Wireshark&logoColor=white" />
    <img src="https://img.shields.io/badge/-Snort-FF0000?&style=for-the-badge&logoColor=white" />
</div>

<!-- Add these once you've completed the labs that use them:
    <img src="https://img.shields.io/badge/-Microsoft_Sentinel-0078D4?&style=for-the-badge&logo=Microsoft&logoColor=white" />
    <img src="https://img.shields.io/badge/-Splunk-000000?&style=for-the-badge&logo=Splunk&logoColor=white" />
    <img src="https://img.shields.io/badge/-Suricata-EF3B2D?&style=for-the-badge&logo=Suricata&logoColor=white" />
-->

## 📜 Certifications

🎯 **Currently pursuing**
- AWS Certified Cloud Practitioner → **AWS Certified Security – Specialty**
- HashiCorp Terraform Associate
- Burp Suite Certified Practitioner (BSCP)

<!-- Once earned, move them up here with a link to the Credly badge or PDF, e.g.:
✅ **Earned**
- [AWS Certified Cloud Practitioner](https://www.credly.com/your-badge-url) · 2026
-->

## 📊 GitHub Stats
<div>
    <img src="https://github-readme-stats.vercel.app/api?username=Elvis-Packet&show_icons=true&hide_border=true" height="150" />
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Elvis-Packet&layout=compact&hide_border=true" height="150" />
</div>

## 📫 Connect
- 💼 LinkedIn — [elvis-mbugua](https://www.linkedin.com/in/elvis-mbugua-89b177331/)
- 🌐 Portfolio — [3lv15p4ck3t.netlify.app](https://3lv15p4ck3t.netlify.app/)
- 📧 Email — [your professional email]
