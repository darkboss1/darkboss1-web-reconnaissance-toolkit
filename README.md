# darkboss1-web-reconnaissance-toolkit



---

## darkboss1-web-reconnaissance-toolkit: One Tool to Rule All Recon

darkboss1-web-reconnaissance-toolkit is a powerful and comprehensive web reconnaissance toolkit tailored to cybersecurity professionals, ethical hackers, and digital investigators. It allows you to uncover hidden information about domains, analyze configurations, detect technologies, and explore archived content from the web.

Whether you're analyzing a target for vulnerabilities or simply exploring the technical details of a website, darkboss1-web-reconnaissance-toolkit provides an all-in-one solution to automate and streamline your reconnaissance process.

---
---

### Key Features

| Feature | Description |
|--------|-------------|
| IP Lookup | Retrieve geolocation and ISP data |
| WHOIS Lookup | Get domain registration information |
| HTTP Header Analysis | Analyze response headers |
| SSL Inspection | Fetch and inspect SSL certificate |
| DNS Enumeration | Gather DNS, Reverse, and Shared DNS records |
| Subdomain Discovery | Identify subdomains using various techniques |
| Port Scanning | Scan and detect open ports |
| Directory Brute-Force | Discover hidden files and directories |
| Web Crawling | Fetch links, robots.txt, and sitemap.xml |
| Tech Detection | Detect technologies used by the website |
| Wayback Machine | View archived pages over time |
| DMARC Analysis | Check domain email authentication (SPF, DKIM, DMARC) |
| Social Media Discovery | Extract social profiles and emails |
| Admin Panel Detection | Identify admin login portals |
| Reverse DNS Lookup | Get hostnames from IP addresses |
| Shared DNS Lookup | Discover other domains on the same DNS server |
| Full Recon Mode | Run all modules for deep analysis |

---
---

### 🧪 Installation

```bash
git clone https://github.com/darkboss1/darkboss1-web-reconnaissance-toolkit.git
cd darkboss1-web-reconnaissance-toolkit
pip3 install -r requirements.txt
```
### ⭔ Example Usage :
```
python -m darkboss1-web-reconnaissance-toolkit.py -whois example.com
```

---

### 🚀 pipx Installation (Recommended)

Install via [`pipx`](https://github.com/pypa/pipx) for isolated, global access:

#### Step 1: Install `pipx`
```bash
python3 -m pip install --user pipx
python3 -m pipx ensurepath
```

#### Step 2: Install darkboss1-web-reconnaissance-toolkit
```bash
pipx install git+https://github.com/darkboss1/darkboss1-web-reconnaissance-toolkit.git
```

---

### 💡 Example Usage

```bash
darkboss1-web-reconnaissance-toolkit -whois example.com
```

---

### 🧭 All Command Options

| Command | Description |
|--------|-------------|
| `-ip <domain>` | IP geolocation info |
| `-headers <domain>` | Show HTTP headers |
| `-whois <domain>` | WHOIS lookup |
| `-ssl <domain>` | SSL certificate analysis |
| `-dns <domain>` | DNS enumeration |
| `-reversedns <domain>` | Reverse DNS lookup |
| `-shareddns <domain>` | Domains on the same DNS |
| `-subdomains <domain>` | Subdomain enumeration |
| `-dmarc <domain>` | DMARC record validation |
| `-crawl <domain>` | Crawl and fetch links |
| `-robots <domain>` | Fetch robots.txt and sitemap.xml |
| `-tech <domain>` | Detect technologies used |
| `-wayback <domain>` | Archive data from Wayback Machine |
| `-social <domain>` | Extract social media/email |
| `-dirscan <domain>` | Directory brute-force |
| `-portscan <domain>` | Port scanning |
| `-admin <domain>` | Admin panel finder |
| `-all <domain>` | Run all tools in one go |

### Optional command for pipx:

```
🔄 To upgrade from GitHub
pipx upgrade darkboss1-web-reconnaissance-toolkit

# If you originally installed using a local directory (pipx install .), then use:
pipx install . --force

❌ To uninstall
pipx uninstall darkboss1-web-reconnaissance-toolkit

# Bonus: Check where it's installed
pipx list
```

---

## 🤝 Contribute

Pull requests and issues are welcome! Found a bug? Have an idea? Let’s collaborate to improve darkboss1-web-reconnaissance-toolkit.

---
---

## 💬 Community & Support

Need help or want to suggest a feature? Join our Discord server and connect with the community.

[![Visit Website](https://serialkey.top)

---
---

<h4 align="center">⭐️ If this project helped you, please give it a star! ⭐️</h4>
