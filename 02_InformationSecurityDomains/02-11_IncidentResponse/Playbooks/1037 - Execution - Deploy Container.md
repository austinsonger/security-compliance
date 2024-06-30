##### **1037 - Execution - Deploy Container**

**(P) Preparation**

1.  Use application control to whitelist approved applications \[1\]
2.  Ensure that servers and workstations are logging to a central location
3.  Deny direct remote access to internal systems \[2\]
4.  Patch asset vulnerabilities
5.  Perform routine inspections of controls/weapons
6.  Ensure antivirus/endpoint protection software is installed on workstations and laptops
7.  Regularly update virus definitions and signatures
8.  Conduct employee security awareness training
9.  Ensure all software is kept up to date
10.  Restrict users to the least privileges required
11.  Utilize threat intelligence to make informed decisions about defensive priorities

**(I) Identification**

1.  Monitor for:  
    a. Suspicious or unknown container images  
    b. Unauthorized API calls  
    c. Anomalous container activity  
    d. Downloads of container images from unknown sources  
    e. Unusual activity in container deployment logs \[3\]
2.  Investigate and clear ALL alerts

**(C) Containment**

1.  Inventory (enumerate & assess)
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
8.  Reset the passwords of any compromised accounts

**(R) Recovery**

1.  Restore to the RPO within the RTO
2.  Assess and address collateral damage
3.  Resolve any related security incidents
4.  Restore affected systems to their last clean backup

**(L) Lessons/Opportunities**

1.  Perform routine cyber hygiene due diligence
2.  Engage external cybersecurity-as-a-service providers and response professionals
3.  Implement policy changes to reduce future risk
4.  Utilize newly obtained threat signatures

**References:**

1.  MITRE ATT&CK Mitigation M1038: https://attack.mitre.org/mitigations/M1038/
2.  MITRE ATT&CK Mitigation M1030: https://attack.mitre.org/mitigations/M1030/
3.  MITRE ATT&CK Technique T1610: https://attack.mitre.org/techniques/T1610/

**Resources:**


*    IT Disaster Recovery Planning: https://www.ready.gov/it-disaster-recovery-plan
*    Report Cybercrime: https://www.ic3.gov/Home/FAQ


  

