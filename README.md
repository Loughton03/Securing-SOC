![image]()

## Introduction
In this project, I constructed a honeynet in Azure and integrated logs from various resources into a Log Analytics workspace. Microsoft Sentinel creates attack maps, triggers alerts, and generates incidents. I initially measured security metrics in the insecure environment over 24 hours, then applied security controls to harden the environment and measured the metrics again for another 24 hours.

## Ratings Before Hardening/Security Controls
## Metrics Before Hardening /Security Controls
## IMPLEMENTATION:
Some Of The Common Remediation Functions To Fix:
Firewall Creations for VMs (linux/Windows)
Email Notifications
Exemptions
Enabling of Microsoft defender for resource manager, DNS, etc.
Azure Backup for virtual machines
Purge Protection
Subnets associated with network security groups 


Some Of The Common Techniques (categories) Fixed during remediation.

  -Defense Evasion (https://attack.mitre.org/tactics/TA0005/)
  -Privilege Escalation (https://attack.mitre.org/tactics/TA0004/)
  -Impact (https://attack.mitre.org/tactics/TA0040/)
  -Persistence (https://attack.mitre.org/tactics/TA0003/)
  -Exfiltration (https://attack.mitre.org/tactics/TA0011/)
  -Lateral Movement (https://attack.mitre.org/tactics/TA0008/)

## Ratings AFTER Hardening/ Security Controls
## Metrics AFTER Hardening/ Security Controls
## Conclusion
