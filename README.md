# subdomain-word-finder

**subdomain-word-finder** — developed by 0xvar  
Version 1.1

A Bash-based tool to find subdomains matching specific keywords right after a wildcard domain.  
It supports both free passive sources (crt.sh, subfinder, assetfinder) and premium APIs (Shodan, VirusTotal, Censys).

---

## 🚀 Features
- Passive subdomain enumeration from:
  - [crt.sh](https://crt.sh)
  - [subfinder](https://github.com/projectdiscovery/subfinder)
  - [assetfinder](https://github.com/tomnomnom/assetfinder)
- API integrations:
  - Shodan
  - VirusTotal
  - Censys
- Keyword-based filtering (e.g., find all subdomains starting with `api`).

---




## 📥 Installation

```bash
git clone https://github.com/0xvar/subdomain-word-finder.git
cd subdomain-word-finder
chmod +x subdomain_word_finder
