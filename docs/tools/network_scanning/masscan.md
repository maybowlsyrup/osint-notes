# Masscan

**Masscan** is a high‑performance TCP port scanner capable of scanning the entire Internet in minutes.  It uses an asynchronous design to achieve extremely high rates (millions of packets per second).

**Features:**

- Extremely fast port scanning using custom TCP/IP stack.  
- Supports output formats compatible with Nmap for downstream processing.  
- Limited service detection (primarily port status).  

**When to use:** when you need to quickly identify open ports across large IP ranges or the Internet.  After masscan finds open ports, follow up with Nmap for deeper enumeration.

**Quickstart:**

```bash
masscan 192.168.1.0/24 -p0-65535 --rate=10000
```

This scans all ports on the subnet at 10,000 packets per second.  Adjust the rate to match network capacity.
