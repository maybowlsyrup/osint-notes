# RustScan

**RustScan** is a modern, fast port scanner written in Rust.  It integrates with Nmap to provide service detection after performing rapid port scans.

**Features:**

- Ultra‑fast port scanning using asynchronous networking.  
- Automatic piping of open ports into Nmap for service detection.  
- Configurable threads and port ranges.  

**When to use:** when you want faster scanning than Nmap alone, but still want Nmap’s rich enumeration capabilities.

**Quickstart:**

```bash
rustscan -a 192.168.1.1 -- -sV -sC
```

RustScan finds open ports on the host and passes them to Nmap with the provided flags.
