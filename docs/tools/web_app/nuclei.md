# Nuclei

**Nuclei** is a fast vulnerability scanner that uses YAML templates to identify security issues in web applications.  The community maintains a large library of templates covering misconfigurations, exposures and known CVEs.

**Features:**

- Modular template system for easy customization.  
- Supports HTTP, DNS, SSL and other protocols.  
- Works well for automated scanning in CI pipelines.  

**When to use:** to quickly assess a target for known issues and misconfigurations using curated templates.

**Quickstart:**

```bash
nuclei -u https://example.com -t cves/ -o nuclei_results.txt
```

This runs CVE templates against the target and saves results to a file.
