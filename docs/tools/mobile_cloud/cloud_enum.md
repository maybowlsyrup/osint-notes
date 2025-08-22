# cloud_enum

**cloud_enum** is an OSINT tool that enumerates publicly accessible resources in Amazon Web Services (AWS), Microsoft Azure and Google Cloud Platform (GCP).  It helps identify misconfigured storage buckets, exposed databases and other cloud assets.

**Usage:** Run the tool with the appropriate flags to search for resources associated with a domain or organization.  

```bash
cloud_enum -m aws -t example.com
```

The tool will output any publicly accessible buckets or endpoints that match the target.
