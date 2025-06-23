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
