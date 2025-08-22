# Scanning

In the scanning phase, testers interrogate the target to identify live hosts, open ports, running services and potential vulnerabilities.  According to the penetration testing methodology【776739838610670†L470-L486】, scanning helps confirm the information collected during reconnaissance and locate technical weaknesses.

Common scanning tasks include:

- **Network scanning** – using tools like `nmap` to discover hosts and open ports【748507295743209†L23-L82】.
- **Service enumeration** – determining what services and versions are running on discovered ports.
- **Vulnerability scanning** – employing automated scanners or scripts to detect known flaws.
- **Web application scanning** – crawling and fuzzing web apps to identify injection points and misconfigurations.

The results of scanning feed into the exploitation phase.
