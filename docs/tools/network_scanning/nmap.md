# Nmap

**Nmap** (Network Mapper) is a free, open‑source utility for network discovery and security auditing.  Often called the Swiss‑army knife of network reconnaissance, Nmap can:

- Scan IP ranges or individual hosts to identify open ports and services.  
- Detect service versions and operating systems using signature detection.  
- Perform scriptable interactions with services for deeper enumeration.  
- Observe firewall and intrusion detection system reactions【748507295743209†L23-L82】.

**When to use:** during the scanning phase of a penetration test to map the attack surface and discover targets.  

**Quickstart:**

```bash
nmap -sV -sC -O 192.168.1.0/24
```

This command performs a version scan (`-sV`), runs default NSE scripts (`-sC`) and attempts OS detection (`-O`) on a /24 subnet.
