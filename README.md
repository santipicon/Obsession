🚀 New pwned machine on DockerLabs! Here’s my writeup for "Obsession" 🎯

A Very Easy box to review web enumeration, brute force, and Linux privilege misconfigurations.

🛠️ Techniques used:
🔹 Recon: Nmap port/service scan.
🔹 Web enum: Dirb found an exposed /backup leaking potential credentials.
🔹 Initial access: SSH brute force with Hydra + rockyou.
🔹 PrivEsc: Misconfigured sudo — Vim runnable as root without password (NOPASSWD). GTFOBins gave a privileged shell. 💻

💡 Lesson: Never leave notes/backups in public web directories, and strictly audit sudo-allowed binaries. A simple text editor can compromise the whole system!
