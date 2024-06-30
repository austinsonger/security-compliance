##### CIRT Playbook Battle Card: **1035 - Credential Access - Credentials from Password Stores**

**(P) Preparation**

1.  Patch asset vulnerabilities
2.  Perform routine inspections of controls/weapons
3.  Ensure antivirus/endpoint protection software is installed on workstations and laptops
4.  Regularly update virus definitions and signatures
5.  Conduct employee security awareness training
6.  Ensure all software is kept up to date
7.  Restrict users to the least privileges required
8.  Utilize threat intelligence to make informed decisions about defensive priorities
9.  Use application control to whitelist approved password storage applications \[1\]
10.  Ensure that servers and workstations are logging to a central location

**(I) Identification**

1.  Monitor for:  
    a. Searches to process memory for common credential keywords, such as; password, pwd, login, store, secure, credentials, etc. \[2\]  
    b. Automated tools scanning memory for passwords  
    c. Storage of passwords in plaintext  
    d. Abnormal activity around all authorized password storage applications  
    e. Use of unauthorized password storage applications  
    f. Access to web browser password storage database files \[3\]
2.  Investigate and clear ALL alerts

**(C) Containment**

1.  Inventory (enumerate & assess) environment technologies
2.  Detect | Deny | Disrupt | Degrade | Deceive | Destroy
3.  Observe -> Orient -> Decide -> Act
4.  Utilize EDR hunter/killer agents to terminate offending processes
5.  Remove the affected system from the network
6.  Determine the source and pathway of the attack
7.  Issue a perimeter enforcement for known threat actor locations

**(E) Eradication**

1.  Close the attack vector
2.  Create forensic backups of affected systems
3.  Perform endpoint/AV scans on affected systems
4.  Reset any compromised passwords
5.  Inspect ALL assets and user activity for IOC consistent with the attack profile
6.  Inspect backups for IOC consistent with the attack profile PRIOR to system recovery
7.  Patch asset vulnerabilities
8.  Remove all instances of credentials that were stored insecurely
9.  Reset the passwords of any compromised accounts

**(R) Recovery**

1.  Restore to the RPO within the RTO
2.  Address any collateral damage
3.  Resolve any related security incidents
4.  Restore affected systems to their last clean backup

**(L) Lessons/Opportunities**

1.  Perform routine cyber hygiene due diligence
2.  Engage external cybersecurity-as-a-service providers and response professionals
3.  Implement policy changes to reduce future risk
4.  Utilize newly obtained threat signatures

**References:**

1.  MITRE ATT&CK Mitigation M1038: https://attack.mitre.org/mitigations/M1038/
2.  MITRE ATT&CK Technique T1555: https://attack.mitre.org/techniques/T1555/
3.  MITRE ATT&CK Technique T1555 Sub-technique 003: https://attack.mitre.org/techniques/T1555/003/

**Resources:**


*    IT Disaster Recovery Planning: https://www.ready.gov/it-disaster-recovery-plan
*    Report Cybercrime: https://www.ic3.gov/Home/FAQ


  

