# sc-200-study
Study for SC-200 Exam



# Configure settings in Microsoft Defender XDR


<img width="815" alt="image" src="https://github.com/user-attachments/assets/3289c9fe-a02b-41b6-93f9-8239d68a78dd" />


# What does XDR do?

- Compromise Detected: User unknowingly opens malware from an unprotected source (e.g., email or USB); Microsoft Defender for Endpoint (MDE) detects the compromise and alerts the security team.

- Access Suspended: MDE flags the device as high-risk, Intune marks it noncompliant, and Microsoft Entra ID Conditional Access blocks access to corporate apps.

- Threat Remediated: MDE removes the threat through automated or manual remediation and updates Microsoft Threat Intelligence to protect other systems.

- Access Restored: Once the device is clean, MDE updates Intune and Microsoft Entra ID to restore access, minimizing risk while preserving user productivity.

# Operations model

-Security Operations Model: Microsoft Defender XDR and Sentinel support a layered SOC model, including Triage (Tier 1), Investigation (Tier 2), and Hunt (Tier 3) teams, each with specialized roles and tools.

-Triage and Automation: Tier 1 analysts quickly resolve high-volume, known threats using automation and integrated XDR tools, escalating complex issues to Tier 2.

-Investigation and Hunting: Tier 2 handles deeper investigations and incident coordination, while Tier 3 proactively hunts undetected threats and supports advanced forensics and response.

-Threat Intelligence: A dedicated team provides strategic and technical insights to all SOC tiers, enhancing detection, response, and long-term defense strategies.

# Mitigate incidents using Microsoft Defender

## Using the Microsoft Defender portal

The Microsoft Defender portal (https://security.microsoft.com/) is a unified security workspace for Microsoft 365, tailored for security teams. It provides integrated protection, detection, investigation, and response across email, devices, identities, apps, and cloud environments.

Key features include:

- Role-based dashboards with relevant insights and alerts based on user roles.

- Centralized view of threats from various Microsoft security tools.

- Streamlined access to security data, incidents, and evidence to aid quick remediation.

Integrated solutions in the portal:

- Defender for Office 365 – Protects email and Office 365 from threats.

- Defender for Endpoint – Provides device threat detection and response.

- Defender XDR – Correlates threat data across Microsoft 365 for complete attack analysis.

- Defender for Cloud Apps – Secures SaaS/PaaS apps with visibility and threat protection.

- Defender for Identity – Detects threats from compromised or malicious users via on-prem AD.

- Defender Vulnerability Management – Identifies and helps fix security misconfigurations and vulnerabilities.

- Defender for IoT – Protects industrial and OT systems.

- Microsoft Sentinel – SIEM/SOAR platform that integrates with Defender XDR for advanced incident management.

## Configure alert and vulnerability notification rules

## Configure Microsoft Defender for Endpoint advanced features

## Configure endpoint rules settings

## Manage automated investigation and response capabilities in Microsoft Defender XDR

## Configure automatic attack disruption in Microsoft Defender XDR

## Investigate security incidents in Microsoft Defender XDR

Azure Sentinel > Incidents > Click on incident > Investigate in Azure Defender > Related entities / Azure Resource, File and Malware >
Next: Take action > Prevent future attacks / Store account public access should be disallowed > remediation steps > quick fix logic > fix > fix 1 resource >
go back to investigate in azure for incident . linked malicous storage artifacts > view playbooks > run playbook

Incident > alerts > click on alert > "An office application ran suspicious commands" / Or whatever the alert is named > 
