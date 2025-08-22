# John the Ripper

**John the Ripper** is a versatile password cracking tool that supports many hash formats and attack techniques.  It can run in single‑hash or multi‑hash modes and can leverage GPU acceleration via the Jumbo version.

**When to use:** to test password strength or recover lost passwords from captures.

**Quickstart:**

```bash
john --wordlist=rockyou.txt --format=raw-md5 hashes.txt
```

John loads the hashes, guesses passwords using the wordlist and prints cracked credentials.
