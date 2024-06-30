##### **1058 - Persistence - Modify Authentication Process**

**(P) Preparation**

1.  Patch asset vulnerabilities
2.  Perform routine inspections of controls/weapons
3.  Maintain Antivirus/EDR application updates
4.  Create network segmentation
5.  Log traffic between network segments
6.  Incorporate threat intelligence
7.  Perform routine inspections of asset backups
8.  Conduct phishing simulations
9.  Conduct user security awareness training
10.  Conduct response training (this PBC)
11.  Enable multi-factor authentication on all authentication interfaces \[1\]
12.  Disallow passwords to be stored using reversible encryption \[1\]

**(I) Identification**

1.  Monitor for:  
    a. changes made to AD security settings related to MFA logon requirements \[1\]  
    b. newly constructed logon behavior across systems that shared accounts, either user, admin, or service accounts \[1\]  
    c. new, unfamiliar DLL files written to a domain controller and/or local computer \[1\]  
    d. suspicious additions to the /Library/Security/SecurityAgentPlugins directory \[1\]
2.  Investigate and clear ALL alerts associated with the impacted assets or accounts
3.  Routinely check firewall, IDS, IPS, and SIEM logs for any unusual activity

**(C) Containment**

1.  Inventory (enumerate & assess)
2.  Detect | Deny | Disrupt | Degrade | Deceive | Destroy
3.  Observe -> Orient -> Decide -> Act
4.  Issue perimeter enforcement for known threat actor locations
5.  Archive scanning related artifacts such as IP addresses, user agents, and requests
6.  Determine the source and pathway of the attack
7.  Fortify non-impacted critical assetsDisable privileges for accounts suspected of compromise \[1\]

**(E) Eradication**

1.  Close the attack vector by applying the Preparation steps listed above
2.  Perform endpoint/AV scans on targeted systems
3.  Reset any compromised passwords
4.  Inspect ALL assets and user activity for IOC consistent with the attack profile
5.  Inspect backups for IOC consistent with the attack profile PRIOR to system recovery
6.  Patch asset vulnerabilities

**(R) Recovery**

1.  Restore to the RPO (Recovery Point Objective) within the RTO (Recovery Time Objective)
2.  Address any collateral damage by assessing exposed technologies
3.  Resolve any related security incidents
4.  Restore affected systems to their last clean backup

**(L) Lessons/Opportunities**

1.  Perform routine cyber hygiene due diligence
2.  Engage external cybersecurity-as-a-service providers and response professionals
3.  Implement policy changes to reduce future risk
4.  Utilize newly obtained threat signatures
5.  Avoid opening email and attachments from unfamiliar senders
6.  Avoid opening email attachments from senders that do not normally include attachments
7.  Remember that data and events should not be viewed in isolation but as part of a chain of behavior that could lead to other activities

**References:**

1.  MITRE ATT&CK Technique T1556: https://attack.mitre.org/techniques/T1556/

**Resources:**


*    IT Disaster Recovery Planning: https://www.ready.gov/it-disaster-recovery-plan
*    Report Cybercrime: https://www.ic3.gov/Home/FAQ


  

