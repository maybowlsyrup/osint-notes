# hashcat

**hashcat** is a fast password recovery tool that uses CPU and GPU acceleration to crack hashed passwords.  It supports a wide range of hash algorithms and attack modes (dictionary, brute force, rule‑based, combinator, mask, etc.).

**When to use:** to crack password hashes obtained from password dumps or captured network traffic.

**Quickstart:**

```bash
hashcat -m 0 -a 0 hashes.txt wordlist.txt
```

Here `-m 0` specifies MD5 hashes and `-a 0` uses a dictionary attack.
