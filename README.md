I am a new ethical hacker and I understand the pain of having to download a ton of tools, just to not really understand what I am doing. I want to developt a a tool that has everything a new ethical hacker needs to understand the basics of the most common tools. Some tools like nmap, metasploit, and burp suite.
If you want to help me developt this tool reach out to me and I will get back to you, hopefully soon.

Basic tree:
  Kumo - Penetration Testing Toolkit

├── Reconnaissance
│   ├── Host Discovery (Ping Sweep)
│   ├── Port Scanning (TCP Connect Scan)
│   ├── Service Detection (Basic Banner Grabbing)

├── Password Cracking
│   ├── Dictionary Attack
│   │   ├── Wordlist Loading
│   │   ├── Hash Type Identification (Basic)
│   ├── Brute-Force Attack
│   │   ├── Character Set Configuration
│   │   ├── Length Configuration

├── Exploitation
│   ├── Exploit Selection (Based on Recon Results)
│   ├── Payload Delivery (Simple File Upload, Command Injection)
│   ├── Listener (Catch Reverse Shell)

├── Proxy Tool
│   ├── HTTP/HTTPS Interception
│   ├── Request Modification
│   ├── Response Viewing
│   ├── Forward Traffic
│   ├── SSL Stripping (Optional)

├── Core
│   ├── CLI Interface
│   ├── Help Command
│   ├── Exit Command
│   ├── Configuration (Future - Basic Settings)
│   ├── Logging (Future)
