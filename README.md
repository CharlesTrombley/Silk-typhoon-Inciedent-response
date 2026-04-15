Incident Response Case Study – Exchange Compromise Investigation


After three days of training to build and operate SimSpace, the platform we will use for future cyber training and for creating labs for CCDC, our team participated in a live incident response exercise on April 2nd, 2026.

The event schedule included a 9:00 AM - 10:30 AM LiveFire Exercise and a 1:00 PM - 2:30 PM LiveFire Review Session. During the exercise, our team successfully identified every attack item in the scenario. The investigation went well, and our team finished as the winning team.

Investigated multi-stage intrusion involving brute force, credential dumping (Mimikatz), lateral movement, and email exfiltration.
Analyzed Windows Event Logs, PowerShell logs, and Security Onion data.
Reconstructed attacker timeline and mapped techniques to MITRE ATT&CK.
Identified indicators of compromise and root cause.




<img src="1_simspace_presentation.webp" alt="Logo" width="50%">

Overview
This case study documents a multi-stage compromise affecting a Windows domain and Microsoft Exchange environment. The attacker obtained administrative access, executed PowerShell-based tooling, dumped credentials with Mimikatz, moved laterally through SMB, accessed Exchange, exported mailbox data, collected local files, staged data, and cleared logs to reduce visibility.

The investigation relied on Windows Event Logs, PowerShell logging, and endpoint/network telemetry to reconstruct activity and identify the scope of compromise.

