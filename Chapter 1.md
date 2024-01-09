# Security Aims and Objectives 

## Understanding Security Fundamentals

### CIA Triad

**Confidentiality**: Prevents the disclosure of data to unathorized people so only authorized people have access to the data; "need-to-know basis"
- Two types of Encryption:
  1. Symmetric: secret key
  2. Asymmetric: public key and private key

**Integrity**: Ensure data has not been tampered with. This is accomplished through hashing. You can encrypt the hash message and compare the beginning and ending hash. If the has is different then the data has been tampered with. 
- Two most common hashing algorithms: (The higher the number of bits, the more secure, and the lower the number, the faster it is.)
  1. 160-bit Secure Hash Algorithm Version 1 (SHA1).
  2. 128-bit Message Digest Version 5 (MD5). 

**Availability**: Ensure data is always available
  1. RAID - Redundant Array of Independant Disks, allows one or two disks to fail while still keeping the data accessible. 
  2. HVAC - YES that HVAC, Heating Ventilation Air Conditioning; regulates temperature for critical servers. 

Least Privelege
- A user has the most-limited access required to perform their role. Also "need-to-know basis".

Defense in Depth  
- Companies data is protect with a series of protective layers. If one layer fails to thrawt an attack the next layer will already be in place. 

### Control Types

3 Main Categories: **Managerial, Operational, Technical**

**Managerial**
- Written by managers to create policies and procedures to reduce risk within the organization and for the company. They encompass regulatory frameworks so that companies stay legally compliant. EX: NIST, CIS, ISO/IEC 27001
- Annual Risk Assessment: Financial directors and IT managers will look at all of their risks in financials and IT infrastructure & add it to a risk register.
- Pen Testing/Vunerability Scan: A pen test is a more indepth intrusive look at your envrionment and attempt to exploit vulnerabilities. This can be completed by a third party or an internal team. 

**Operational**
- These are day-to-day operations.
1. Annual Security Awareness Training: In this training it reminds you of ways to keep the companies data secure. Threats are always evolving so this training is completed annually. 
2. Change Management: A process a company adopts so changes don't cause security risks 

**Technical**
- These are implemented by the IT team to reduce risk to the business.
  A. Firewall Rules
  B. Antivirus/Antimalware
  C. Screen Savers
  D. Screen Filters
  E Intrusion Detection (IDS) and Intrusion Prevention Systems (IPS)

Deterrent Controls
 - CCTV

Detective Controls
- Log Files (WORM; Write Once Read Many) & CCTV Records

Corrective Controls
- Firesupression System in data center
- Restoring data from a backup

Compensating Controls
- Alterantive/Secondary Controls
- Can be used when a primary control has failed or is not available
- EX: Signing in with your guest pass as a new hire until your badge has arrived

Preventative Controls 
- Are in place to deter an attack
- Disable users accounts when they plan to quit
- Operating System Hardening: Patch all vulnerabilites to ensure security
- [DOD: STIG](https://public.cyber.mil/stigs/)

Access Controls
- Identity Access Management
- Indetification, Authentication, Authorization

Discretionary Access Controls
- Similar to New Technolofy File System (NFTS)
- The data creator is responsible for checking who has access to that data.

Mandatory Access Control
- based of classification level of data
- System administrators gives access to data once clearance has been approved

Role-Based Access Control
- A subset of a department carrying out a subset of duties.

Rule-Based Access Control
- Employees can only access the campus from 6 AM to 6 PM

Attribute-Based Access Control
- Only users with the executive title "attribute" can read certain data.

Group-Based Access Control
- You are put into groups to simplify access

**Linux File Permissions**

Physical Security Controls
- Badge, Fence, Signage, Security Officers, Turnstile

Device Protection
- Air Gap, Faraday Cage, Vault, USB Data Blocker
