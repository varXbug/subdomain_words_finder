# subdomain_words_finder
subdomain-word-finder is a Bash-based reconnaissance tool that helps security researchers and bug bounty hunters discover subdomains matching specific keywords after a wildcard domain.

The tool supports:

Passive enumeration using subfinder, assetfinder, and crt.sh.

API integrations with Shodan, VirusTotal, and Censys (via config.conf).

Keyword filtering to detect subdomains that start or contain user-defined terms (e.g., api.example.com, store.example.com).

Flexible configuration: If API keys are provided in config.conf, they are used automatically; otherwise, the tool falls back to free passive sources.

This project aims to simplify subdomain discovery workflows and make it easier to focus on interesting targets like APIs, stores, or other keyword-specific assets
