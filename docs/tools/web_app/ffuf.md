# ffuf

**ffuf** (Fuzz Faster U Fool) is a command‑line web fuzzer written in Go.  It is used for discovering hidden directories, files and subdomains by making HTTP requests with wordlists.

**Features:**

- High speed and low resource usage.  
- Flexible placeholders for directory/file fuzzing, DNS fuzzing or POST data fuzzing.  
- Output in multiple formats (JSON, HTML, CSV).  

**When to use:** when performing content discovery on a web server to find hidden paths or endpoints.

**Quickstart:**

```bash
ffuf -u https://example.com/FUZZ -w /path/to/wordlist.txt
```

This tests each word in the wordlist as a directory or file under the target URL.
