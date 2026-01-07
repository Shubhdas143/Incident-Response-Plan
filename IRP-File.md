<h2>📄Incident Response Plan</h2>

Prepared by: Shubhranshu Shekhar Das – Cybersecurity Student

Designed and documented a comprehensive Incident Response Plan covering phishing, malware, and account compromise scenarios. Applied SOC-standard methodologies including detection, containment, eradication, recovery, and lessons learned, along with a practical mock incident walkthrough.


🔐 1. Phishing Response
---
I. Detection

⦁ User reports a suspicious email or login alert<br>
⦁ Email security gateway flags a phishing message<br>
⦁ Unusual login activity detected from unknown IP/location

II. Containment

⦁ Block the phishing URL and sender domain<br>
⦁ Temporarily disable the affected user account<br>
⦁ Alert other employees about the phishing campaign

III. Eradication

⦁ Remove phishing emails from all mailboxes <br>
⦁ Reset compromised credentials <br>
⦁ Remove malicious inbox rules created by attacker

IV. Recovery

⦁ Restore user account after password reset<br>
⦁ Enforce Multi-Factor Authentication (MFA)<br>
⦁ Monitor account activity for 48–72 hours

V. Lessons Learned

⦁ Conduct phishing awareness training<br>
⦁ Improve email filtering rules<br>
⦁ Encourage early reporting of suspicious emails

🦠 2. Malware Response
---
I. Detection

⦁ Antivirus or EDR alerts on malicious activity<br>
⦁ System shows abnormal behavior (slow performance, pop-ups)<br>
⦁ User reports unexpected file or application behavior

II. Containment

⦁ Isolate infected system from the network<br>
⦁ Disable external devices (USB, removable drives)<br>
⦁ Inform SOC/IT team immediately

III. Eradication

⦁ Remove malware using endpoint security tools<br>
⦁ Delete malicious files and registry entries<br>
⦁ Patch vulnerable applications and OS

IV. Recovery

⦁ Restore system from clean backup if required<br>
⦁ Reconnect system to network after validation<br>
⦁ Monitor endpoint for reinfection

V. Lessons Learned

⦁ Improve endpoint protection policies<br>
⦁ Restrict administrative privileges<br>
⦁ Ensure regular system updates and patching

🔑 3. Account Compromise Response
---
I. Detection

⦁ User reports unauthorized access<br>
⦁ Multiple failed or unusual login attempts detected<br>
⦁ Login activity from unusual geographic location

II. Containment

⦁ Immediately lock the compromised account<br>
⦁ Terminate all active user sessions<br>
⦁ Notify SOC and management team

III. Eradication

⦁ Reset account passwords and revoke access tokens<br>
⦁ Remove unauthorized changes or permissions<br>
⦁ Review logs for lateral movement

IV. Recovery

⦁ Re-enable account after security verification<br>
⦁ Enforce strong password policy and MFA<br>
⦁ Monitor account behavior for anomalies

V. Lessons Learned

⦁ Strengthen access control mechanisms<br>
⦁ Enforce MFA across all critical systems<br>
⦁ Educate users on credential security

🧪 4. Mock Incident Scenario
---

Incident Description:
An employee received a phishing email impersonating the IT department. The user clicked the link and entered their login credentials. The attacker used these credentials to access the user’s email account.

I. Detection

⦁ User reported a suspicious email<br>
⦁ SOC detected login from an unknown IP address

II. Containment

⦁ Compromised account was immediately locked<br>
⦁ Phishing URL was blocked across the organization

III. Eradication

⦁ Password reset performed for the affected user<br>
⦁ Malicious inbox rules removed

IV. Recovery

⦁ Account restored after identity verification<br>
⦁ MFA enabled on the account

V. Lessons Learned

⦁ Organization-wide phishing awareness training conducted<br>
⦁ Email security controls enhanced
