##### CIRT Playbook Battle Card: **1048 - Credential Access - Brute Force**

**(P) Preparation**

1.  Patch asset vulnerabilities
2.  Perform routine inspections of controls/weapons
3.  Ensure antivirus/endpoint protection software is installed on workstations and laptops
4.  Confirm that servers and workstations are logging to a central location
5.  Review firewall, IDS, and IPS rules routinely and update based on the needs of the environment
6.  Restrict access to critical assets as needed
7.  Conduct employee security awareness training
8.  Restrict users to the least privileges required
9.  Set lockout policies to lock accounts after a certain number of failed login attempts
10.  Enable multi-factor authentication wherever possible
11.  Use strong password policies on all accounts

**(I) Identification**

1.  Monitor for high volumes of authentication failures through any of the following methods:  
    a. Password guessing \[1\]  
    b. Password Cracking \[2\]  
    c. Password Spraying \[3\]  
    d. Credential Stuffing \[4\]
2.  Investigate and clear ALL alerts associated with the impacted assets
3.  Routinely check firewall, IDS, IPS, and SIEM logs for any unusual activity

**(C) Containment**

1.  Inventory (enumerate & assess)
2.  Detect | Deny | Disrupt | Degrade | Deceive | Destroy
3.  Observe -> Orient -> Decide -> Act
4.  Issue perimeter enforcement for known threat actor locations
5.  Archive scanning related artifacts such as IP addresses, user agents, and requests
6.  Determine the source and pathway of the attack

**(E) Eradication**

1.  Close the attack vector by applying the Preparation steps listed above
2.  Perform endpoint/AV scans on targeted systems
3.  Reset any compromised passwords
4.  Inspect ALL assets and user activity for IOC consistent with the attack profile
5.  Inspect backups for IOC consistent with the attack profile PRIOR to system recovery
6.  Patch asset vulnerabilities
7.  Reset accounts that have been breached immediately

**(R) Recovery**

1.  Restore to the RPO within the RTO
2.  Address any collateral damage by assessing exposed technologies
3.  Resolve any related security incidents
4.  Restore affected systems to their last clean backup

**(L) Lessons/Opportunities**

1.  Perform routine cyber hygiene due diligence
2.  Engage external cybersecurity-as-a-service providers and response professionals
3.  Implement policy changes to reduce future risk
4.  Utilize newly obtained threat signatures
5.  Remember that data and events should not be viewed in isolation but as part of a chain of behavior that could lead to other activities

**References:**

1.  MITRE ATT&CK Technique T1110.001: https://attack.mitre.org/techniques/T1110/001/
2.  MITRE ATT&CK Technique T1110.002: https://attack.mitre.org/techniques/T1110/002/
3.  MITRE ATT&CK Technique T1110.003: https://attack.mitre.org/techniques/T1110/003/
4.  MITRE ATT&CK Technique T1110.004: https://attack.mitre.org/techniques/T1110/004/

**Resources:**


*    IT Disaster Recovery Planning: https://www.ready.gov/it-disaster-recovery-plan
*    Report Cybercrime: https://www.ic3.gov/Home/FAQ


  

