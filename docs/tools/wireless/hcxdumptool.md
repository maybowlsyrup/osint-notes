# hcxdumptool

**hcxdumptool** captures WPA handshake and PMKID packets from Wi‑Fi networks.  It is designed for use with `hashcat` to perform offline cracking.

**Workflow:**

- Capture traffic using `hcxdumptool` with a compatible Wi‑Fi adapter.  
- Extract PMKID or handshake hashes from the capture with `hcxpcapngtool`.  
- Crack the hashes using `hashcat`.

**Note:** Use this tool only on networks you own or have explicit permission to test.
