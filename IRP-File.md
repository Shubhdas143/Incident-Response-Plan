📄 **Incident Response Plan**

Prepared by: Shubhranshu Shekhar Das – Cybersecurity Student

Designed and documented a comprehensive Incident Response Plan covering phishing, malware, and account compromise scenarios. Applied SOC-standard methodologies including detection, containment, eradication, recovery, and lessons learned, along with a practical mock incident walkthrough.
---
🔐 1. Phishing Response
I. Detection

⦁ User reports a suspicious email or login alert
⦁ Email security gateway flags a phishing message
⦁ Unusual login activity detected from unknown IP/location

II. Containment

⦁ Block the phishing URL and sender domain
⦁ Temporarily disable the affected user account
⦁ Alert other employees about the phishing campaign

III. Eradication

⦁ Remove phishing emails from all mailboxes
⦁ Reset compromised credentials
⦁ Remove malicious inbox rules created by attacker

IV. Recovery

⦁ Restore user account after password reset
⦁ Enforce Multi-Factor Authentication (MFA)
⦁ Monitor account activity for 48–72 hours

V. Lessons Learned

⦁ Conduct phishing awareness training
⦁ Improve email filtering rules
⦁ Encourage early reporting of suspicious emails

🦠 2. Malware Response
I. Detection

⦁ Antivirus or EDR alerts on malicious activity
⦁ System shows abnormal behavior (slow performance, pop-ups)
⦁ User reports unexpected file or application behavior

II. Containment

⦁ Isolate infected system from the network
⦁ Disable external devices (USB, removable drives)
⦁ Inform SOC/IT team immediately

III. Eradication

⦁ Remove malware using endpoint security tools
⦁ Delete malicious files and registry entries
⦁ Patch vulnerable applications and OS

IV. Recovery

⦁ Restore system from clean backup if required
⦁ Reconnect system to network after validation
⦁ Monitor endpoint for reinfection

V. Lessons Learned

⦁ Improve endpoint protection policies
⦁ Restrict administrative privileges
⦁ Ensure regular system updates and patching

🔑 3. Account Compromise Response
I. Detection

⦁ User reports unauthorized access
⦁ Multiple failed or unusual login attempts detected
⦁ Login activity from unusual geographic location

II. Containment

⦁ Immediately lock the compromised account
⦁ Terminate all active user sessions
⦁ Notify SOC and management team

III. Eradication

⦁ Reset account passwords and revoke access tokens
⦁ Remove unauthorized changes or permissions
⦁ Review logs for lateral movement

IV. Recovery

⦁ Re-enable account after security verification
⦁ Enforce strong password policy and MFA
⦁ Monitor account behavior for anomalies

V. Lessons Learned

⦁ Strengthen access control mechanisms
⦁ Enforce MFA across all critical systems
⦁ Educate users on credential security

🧪 4. Mock Incident Scenario

Incident Description:
An employee received a phishing email impersonating the IT department. The user clicked the link and entered their login credentials. The attacker used these credentials to access the user’s email account.

I. Detection

⦁ User reported a suspicious email
⦁ SOC detected login from an unknown IP address

II. Containment

⦁ Compromised account was immediately locked
⦁ Phishing URL was blocked across the organization

III. Eradication

⦁ Password reset performed for the affected user
⦁ Malicious inbox rules removed

IV. Recovery

⦁ Account restored after identity verification
⦁ MFA enabled on the account

V. Lessons Learned

⦁ Organization-wide phishing awareness training conducted
⦁ Email security controls enhanced
