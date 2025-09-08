🔐 Linux Auditing & System Hardening
📌 Overview

A cybersecurity project focused on auditing and hardening a Linux system by checking firewall status, SSH configurations, file permissions, suspicious processes, and rootkits.

Final Security Score: 80/100 → Moderately secure with improvement opportunities.

🛠️ Tools

Bash scripting (automation)

UFW – firewall management

chkrootkit – rootkit detection

System utilities: ps, ls, cat, chmod

🚀 Key Steps

Automated audit script (audit.sh)

Firewall verification (ufw status)

SSH config check (root login disabled, password login enabled)

File permission audit (/etc/passwd, /etc/shadow)

Suspicious process monitoring (ps aux)

Rootkit detection (chkrootkit)

📊 Risks & Fixes

SSH Config: Disable password logins → use SSH keys

Firewall: Restrict SSH access to trusted IPs

Processes: Investigate high CPU jobs

Rootkits: Schedule weekly scans

📘 Conclusion

The system is reasonably secure but can be improved to 90+/100 by tightening SSH, firewall, and automated scans.

🙌 Author: Pusarla Vinay
