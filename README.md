# HoneyPot
# Honeypot Assignment

**Time spent:** **4** hours spent in total

**Objective:** Create a honeynet using MHN-Admin. Present your findings as if you were requested to give a brief report of the current state of Internet security. Assume that your audience is a current employer who is questioning why the company should allocate anymore resources to the IT security team.

### MHN-Admin Deployment (Required)

**Summary:** How did you deploy it? Did you use GCP, AWS, Azure, Vagrant, VirtualBox, etc.?
I used GCP by following the guide in the project instructions



### Dionaea Honeypot Deployment (Required)

**Summary:** Briefly in your own words, what does dionaea do?
Dionnaea can create vulnerabilities that tools like nmap or other vulnerability scanner can easily find and use the "clues" that left by the attacker to attack back or do something else. MHN is an open source framework that help user to view attacks and manage snort/sniffing rules, deploy scripts, connect, register, send intrusion logs, and dinaea is the vulnerable server that reachable in public domin.



### Database Backup (Required) 

**Summary:** What is the RDBMS that MHN-Admin uses? What information does the exported JSON file record?

MHN-Admin uses MongoDB
In the JSON file, it contains protocal's name, time of attack, source ip, source and destination port, identifier and the name of honeypot

The JSON file is in the same repository

### Deploying Additional Honeypot(s) (Optional)

#### X Honeypot

**Summary:** What does this honeypot simulate and do for a security researcher?



### Malware Capture and Identification (Optional)

#### X Malware

**Summary:** How did you find it? Which honeypot captured it? What does each malware do?

MD5 Hash: *Run `md5sum` on the file and record the hash here.*

SHA1 Hash: *Run `sha1sum` on the file and record the hash here.*


## Notes

Describe any challenges encountered while doing the assignment.
