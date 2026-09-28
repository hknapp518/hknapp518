<div align="center">

# Harrison Knapp

### Azure Cloud Security • Detection Engineering • DFIR

**Security Engineer building and validating controls across the Microsoft security ecosystem**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Harrison%20Knapp-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/harrison-knapp-175aes)
[![GitHub](https://img.shields.io/badge/GitHub-hknapp518-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/hknapp518)

![AZ-500](https://img.shields.io/badge/AZ--500-Azure%20Security-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![SC-200](https://img.shields.io/badge/SC--200-Security%20Operations-0078D4?style=flat-square&logo=microsoft&logoColor=white)
![CySA+](https://img.shields.io/badge/CySA%2B-Security%20Analytics-EA1D2C?style=flat-square)
![Security+](https://img.shields.io/badge/Security%2B-Cybersecurity-EA1D2C?style=flat-square)
![PenTest+](https://img.shields.io/badge/PenTest%2B-Penetration%20Testing-EA1D2C?style=flat-square)

</div>

---

## Security Engineering Portfolio

> I build security controls, test them against realistic failure scenarios, investigate what breaks, and use the evidence to improve the architecture and detections.

| Project | Description |
| --- | --- |
| [**Azure Ransomware Honeypot — DFIR & Detection Engineering**](https://github.com/hknapp518/Azure-SQL-Honeypot-DFIR-) | Built and instrumented an Azure Windows/MySQL honeypot that captured 307 Windows logon events, 239 failed Windows logons, 73 failed MySQL authentications, 152 external MySQL connections, and 112 external root connections. Investigated a ransomware/extortion attack involving 34 destructive SQL operations and 5 high-impact administrative actions in ~3 seconds. Recovered 5,298 synthetic records, eliminated remote `root@'%'` access, hardened the original attack path, and engineered 3 incident-derived Sentinel detections, expanding coverage from 2 authentication rules to 5 enabled analytics. |
| [**Azure Healthcare Security Landing Zone**](https://github.com/hknapp518/Azure-Healthcare-Security-Landing-Zone) | Designed and validated a healthcare-focused Azure security architecture using Management Groups, Azure Policy, RBAC, hub-spoke networking, NSGs, Private Link, Key Vault, customer-managed encryption keys, centralized logging, and KQL detection. Tested controls, diagnosed policy scope and platform dependency failures, remediated implemented controls, and documented production gaps through a SOC 2/HIPAA security-readiness assessment. |
| [**Microsoft Purview Data Security & Governance**](https://github.com/hknapp518/Microsoft-Purview-Governance-Lab) | Engineered and tested Microsoft Purview data-protection controls using sensitivity labels, custom Sensitive Information Types, DLP, and policy enforcement. Built a NERC CIP-inspired BCSI scenario that blocks unauthorized external sharing, generates Defender XDR alerts, and streams security telemetry through Azure Event Hub into Splunk for investigation. |
| [**Splunk Detection Engineering Lab**](https://github.com/hknapp518/Detection-HomeLab) | Built a detection environment for security telemetry ingestion, correlation, investigation, and alerting. Developed detection logic and dashboards across Windows, firewall, and endpoint telemetry to investigate simulated security events. |

---

## Microsoft Security Stack

<div align="center">

![Azure](https://img.shields.io/badge/Azure-Cloud%20Security-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Sentinel](https://img.shields.io/badge/Microsoft%20Sentinel-SIEM%20%2F%20SOAR-5C2D91?style=for-the-badge&logo=microsoft&logoColor=white)
![Defender](https://img.shields.io/badge/Defender%20XDR-Endpoint%20%2F%20Identity-00A4EF?style=for-the-badge&logo=microsoft&logoColor=white)
![Entra](https://img.shields.io/badge/Entra%20ID-IAM%20%2F%20Zero%20Trust-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)

![Intune](https://img.shields.io/badge/Intune-Endpoint%20Management-0078D4?style=flat-square&logo=microsoft&logoColor=white)
![KQL](https://img.shields.io/badge/KQL-Detection%20Engineering-5C2D91?style=flat-square)
![PowerShell](https://img.shields.io/badge/PowerShell-Automation-5391FE?style=flat-square&logo=powershell&logoColor=white)
![Purview](https://img.shields.io/badge/Microsoft%20Purview-Data%20Security-0078D4?style=flat-square&logo=microsoft&logoColor=white)
![Splunk](https://img.shields.io/badge/Splunk-SIEM-000000?style=flat-square&logo=splunk&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-Database%20Telemetry-4479A1?style=flat-square&logo=mysql&logoColor=white)

</div>

---

## How I Engineer Security

<div align="center">

### Design → Build → Test → Investigate → Remediate → Validate

</div>

### Areas of Focus

```text
Cloud Security        Azure architecture • network segmentation • Policy • Key Vault
Identity Security     Entra ID • RBAC • Conditional Access • MFA • least privilege
Detection Engineering Microsoft Sentinel • KQL • behavioral analytics • rule tuning
Endpoint Security     Defender XDR • Intune • investigation • containment
Data Security         Microsoft Purview • DLP • sensitive information protection
DFIR                  Evidence collection • scoping • reconstruction • recovery
Automation            PowerShell • Python • Azure CLI
```
