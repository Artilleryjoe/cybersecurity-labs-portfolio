
**Description**
Simulated a credential compromise scenario to demonstrate how stolen or weak credentials can lead to unauthorized system access.

**Tools Used**
Hydra – for brute-force attacks on SSH and HTTP login portals

Burp Suite – for intercepting and manipulating web login requests

Gophish – for phishing simulation (optional)

John the Ripper – for password hash cracking

Metasploit – for post-compromise exploitation

Wireshark – for network traffic analysis

**Key Steps**
Identified target login services (SSH/Web App)

Launched brute-force attack using Hydra

Captured and reused valid credentials for access

Verified access via successful login to the target system

Optionally escalated access or performed lateral movement

Monitored traffic and logged suspicious login behavior

**Outcome**
Successfully demonstrated the risks of weak or reused credentials. Gained unauthorized access and documented the process to highlight detection opportunities and the importance of secure password policies.

