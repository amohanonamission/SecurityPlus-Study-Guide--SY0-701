
## **SECURITY+ PRACTICE QUESTIONS**

This section contains a curated set of **50 practice questions** designed to simulate the style, scope, and difficulty of the **Comptia Security+** exam.

These questions focus on:

- Concept clarity
- Mixture of scenario-based, PBQ-style, and recall that I used for my preparation.
- Understanding why an answer is correct (and why others are not)

The goal is not just memorization, but **pattern recognition**, which is key to passing Security+ SY0-701.

---

## How to Use

- Attempt questions without looking at answers first  
- Review explanations carefully  
- Identify weak areas and revise those topics  
- Repeat until you can confidently recognize patterns  

---

> Tip: Questions are formed with the help of ChatGPT. Once you go through these, you can paste these into a prompt and ask any LLM to generate more of them.

**Answer key is at the end.**

Read slowly. Treat each one like an exam moment. Do deep research on any question you attempt wrongly.

---

### **1.**

A security analyst detects multiple failed login attempts from different IPs targeting the same user account within seconds.
What attack is most likely happening?
A. Password spraying
B. Brute force
C. Credential stuffing
D. Dictionary attack

### **2.**

A company wants to ensure that *only* approved software can run on corporate laptops.
Which security control helps achieve this?
A. Blacklisting
B. Whitelisting
C. Sandboxing
D. Integrity monitoring

### **3.**

An attacker intercepts traffic between a user and a website, replacing the session cookie.
Which attack is this?
A. Replay
B. Session hijacking
C. MITM
D. Downgrade attack

### **4.**

Which protocol uses port 636?
A. LDAPS
B. IMAPS
C. FTPS
D. HTTPS

### **5.**

Which of the following is the *strongest* form of authentication?
A. Password and PIN
B. Password and OTP
C. Smart card and PIN
D. Username and password

### **6.**

A company wants to reduce *vendor lock-in* while moving to the cloud.
Which model gives the most flexibility?
A. SaaS
B. PaaS
C. IaaS
D. FaaS

### **7.**

A SOC analyst sees hundreds of outbound DNS queries to random domain names.
Which attack is indicated?
A. DNS poisoning
B. DDoS
C. Data exfiltration via DNS
D. ARP spoofing

### **8.**

You need to ensure emails cannot be *altered* in transit.
Which provides this?
A. Confidentiality
B. Integrity
C. Availability
D. Non-repudiation

### **9.**

An attacker modifies a database without authorization. This violates:
A. Integrity
B. Availability
C. Confidentiality
D. Authentication

### **10.**

What is the main purpose of a *hot site*?
A. Data backups
B. Immediate recovery
C. Manual failover
D. Testing DR plans

---

### **11.**

Which hashing algorithm is considered broken?
A. SHA-256
B. MD5
C. SHA-3
D. bcrypt

### **12.**

A user receives a fake SMS message asking them to “verify their bank card.”
This is:
A. Phishing
B. Vishing
C. Smishing
D. Whaling

### **13.**

Which authentication method eliminates passwords entirely?
A. SSO
B. Federation
C. Passwordless
D. MFA

### **14.**

Firewall rule:
`ALLOW 10.10.0.0/16 → ANY : PORT 443`
This allows:
A. All HTTPS from the 10.10 network
B. All HTTP from the 10.10 network
C. All inbound traffic to 10.10
D. Outbound traffic only

### **15.**

A company wants to detect modifications to system files.
Which tool is best?
A. DLP
B. HIDS
C. SIEM
D. WAF

---

### **16.**

A password like “T!m3T0F1x” is vulnerable to:
A. Brute force
B. Dictionary
C. Social engineering
D. Rainbow table

### **17.**

Your organization wants to prevent an attacker from escalating privileges after a breach.
Which principle helps?
A. Least privilege
B. Separation of duties
C. Zero trust
D. Mandatory vacations

### **18.**

A private key is lost. What must happen?
A. Reissue CSR
B. Revoke certificate
C. Change hashing algorithm
D. Regenerate CA root

### **19.**

A misconfigured S3 bucket allowing global read-access is a violation of:
A. IAM
B. VPC
C. Availability
D. SIEM

### **20.**

A cyber insurance provider asks for proof of compensating controls.
This refers to:
A. Controls replacing missing security measures
B. Controls monitoring employee activity
C. Controls with legal implications
D. Controls used in DR only

---

### **21.**

A tool that identifies vulnerabilities but does NOT exploit them is a:
A. Scanner
B. Fuzzer
C. Pen test
D. Exploit kit

### **22.**

A user can log in to multiple services with one credential.
This is:
A. MFA
B. Federation
C. SSO
D. RBAC

### **23.**

A worm spreads across the network by exploiting SMB.
This is an example of:
A. Lateral movement
B. Privilege escalation
C. Persistence
D. Exfiltration

### **24.**

A company isolates its OT (industrial systems) network from IT users.
This is:
A. Network segmentation
B. Encoding
C. SSL offloading
D. Geofencing

### **25.**

A developer commits API keys to GitHub by accident.
Which response is MOST correct?
A. Delete the repo
B. Revoke the keys immediately
C. Rotate HTTPS
D. Change hash function

---

### **26.**

A brute-force attack is best blocked by:
A. IPS
B. Account lockout
C. DLP
D. WAF

### **27.**

What is the purpose of a CSR?
A. Validate CA identity
B. Request a certificate
C. Validate OCSP stapling
D. Encrypt private keys

### **28.**

A log entry shows “TCP SYN floods.”
This indicates:
A. SQL injection
B. DDoS
C. Smurf attack
D. Credential stuffing

### **29.**

What provides confidentiality for data *at rest*?
A. Hashing
B. TLS
C. Encryption
D. Digital signatures

### **30.**

A user claims they didn’t send an email, but logs show they did.
Which concept prevents this denial?
A. Confidentiality
B. Integrity
C. Availability
D. Non-repudiation

---

### **31.**

The MOST secure wireless network protocol is:
A. WEP
B. WPA2-PSK
C. WPA3-SAE
D. TKIP

### **32.**

A penetration tester is hired and given full access to internal architecture.
This is:
A. Black box
B. White box
C. Gray box
D. Blind test

### **33.**

A risk assessment states: high likelihood, low impact.
The best response is:
A. Avoid
B. Transfer
C. Accept
D. Mitigate

### **34.**

A phishing email includes a real company logo and sender address.
This is:
A. Impersonation
B. Spoofing
C. Pretexting
D. Tailgating

### **35.**

Which control is *technical*?
A. Security awareness training
B. Encryption
C. Policies
D. Hiring procedures

---

### **36.**

Your SIEM shows a user who logs in from Canada and 10 minutes later from India.
This is:
A. Geofencing
B. Impossible travel
C. Federation
D. Zero day

### **37.**

A malicious insider deletes backups.
Which threat type is this?
A. Hacktivist
B. Insider threat
C. Competitor
D. Script kiddie

### **38.**

What does SAML mainly provide?
A. Network encryption
B. Single sign-on between organizations
C. Data masking
D. Secure APIs

### **39.**

A company sets up cameras and smart locks. These are:
A. Administrative controls
B. Technical controls
C. Physical controls
D. Compensating controls

### **40.**

Which RAID level provides fault tolerance using parity?
A. RAID 0
B. RAID 1
C. RAID 5
D. RAID 10

---

### **41.**

Which tool captures and analyzes network traffic?
A. Wireshark
B. Nmap
C. Nessus
D. Kali

### **42.**

What does a DR plan primarily focus on?
A. Preventing attacks
B. Restoring operations after disaster
C. Risk avoidance
D. Securing cloud apps

### **43.**

Public and private key pairs are used in:
A. Symmetric encryption
B. Asymmetric encryption
C. Hashing
D. Obfuscation

### **44.**

A new vulnerability with no patch is discovered.
This is a:
A. Zero-day
B. Logic bomb
C. Backdoor
D. Firmware attack

### **45.**

A company wants to ensure that users cannot deny having approved a transaction.
Which mechanism helps?
A. Tokenization
B. Digital signature
C. Hashing
D. SSL termination

---

### **46.**

An attacker sends specially crafted packets to crash a service.
Which attack is this?
A. Injection
B. Buffer overflow
C. Directory traversal
D. Pass-the-hash

### **47.**

A user plugs in a USB drive they found in the hallway. Malware installs automatically.
What attack type is this?
A. Watering hole
B. Dumpster diving
C. Social engineering bait
D. Influence campaign

### **48.**

An auditor wants to identify misconfigured permissions.
Which model is used to define roles?
A. DAC
B. MAC
C. ABAC
D. RBAC

### **49.**

Which best describes patch management?
A. Removing root certificates
B. Updating systems to reduce vulnerabilities
C. Auditing file permissions
D. Encrypting logs

### **50.**

Which tool verifies the *integrity* of a downloaded file?
A. Hash comparison
B. TLS
C. Diffie-Hellman
D. SFTP

---

# **ANSWER KEY**

1 C
2 B
3 B
4 A
5 C
6 C
7 C
8 B
9 A
10 B
11 B
12 C
13 C
14 A
15 B
16 A
17 A
18 B
19 A
20 A
21 A
22 C
23 A
24 A
25 B
26 B
27 B
28 B
29 C
30 D
31 C
32 B
33 C
34 A
35 B
36 B
37 B
38 B
39 C
40 C
41 A
42 B
43 B
44 A
45 B
46 B
47 C
48 D
49 B
50 A
