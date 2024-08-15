## Securing a SOC Environment To Be NIST SP 800-53 R5 Compliant

![image](https://imgur.com/nnRtlHr.png)

## Introduction
In this project, I enhanced the Honeynet I created in the previous project (Building a SOC + Honeynet) by aligning it with the NIST SP 800-53 R5 regulatory compliance standards. I addressed several non-compliant controls identified within the security metrics in Microsoft Azure to strengthen the environment, reduce or eliminate attacks, and ensure ongoing compliance.


## Ratings Before Hardening/Security Controls

![Security Posture](https://imgur.com/pTwpHay.png)

![Security Posture](https://imgur.com/zimK22r.png)

## Metrics Before Hardening /Security Controls

![Compliance Controls](https://imgur.com/xcp3S5v.png)

![Quick Fixes](https://imgur.com/fbE1YOU.png)

![Compliance Controls](https://imgur.com/1aRo0hQ.png)


## IMPLEMENTATION:

![Severity Level](https://i.imgur.com/SkGfAaj.png)

Some Of The Common Remediation Functions To Fix:
- Firewall Creations for VMs (linux/Windows)
- Email Notifications
- Exemptions
- Enabling of Microsoft defender for resource manager, DNS, etc.
- Azure Backup for virtual machines
- Purge Protection
- Subnets associated with network security groups 


Some Of The Common Techniques (categories) Fixed during remediation.

  - Defense Evasion (https://attack.mitre.org/tactics/TA0005/)
  - Privilege Escalation (https://attack.mitre.org/tactics/TA0004/)
  - Impact (https://attack.mitre.org/tactics/TA0040/)
  - Persistence (https://attack.mitre.org/tactics/TA0003/)
  - Exfiltration (https://attack.mitre.org/tactics/TA0011/)
  - Lateral Movement (https://attack.mitre.org/tactics/TA0008/)

## Ratings AFTER Hardening/ Security Controls
## Metrics AFTER Hardening/ Security Controls
## Conclusion
