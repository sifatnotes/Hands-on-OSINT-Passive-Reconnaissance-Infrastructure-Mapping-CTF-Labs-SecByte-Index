# Hands-on-OSINT-Passive-Reconnaissance-Infrastructure-Mapping-CTF-Labs-SecByte-Index
A practical collection of cybersecurity CTF labs covering Open Source Intelligence (OSINT), active &amp; passive reconnaissance, DNS enumeration, subdomain discovery, WHOIS trails, Google Dorking, metadata extraction, and website fingerprinting.
# OSINT, Passive Reconnaissance & Infrastructure Mapping CTF Labs

Welcome to the **OSINT, Passive Reconnaissance & Infrastructure Mapping CTF Lab Collection**. This repository serves as a structured, searchable catalog of practical cybersecurity labs hosted on Learn SecByte.

This collection covers the critical intelligence-gathering phases of cybersecurity operations—spanning **Passive & Active Reconnaissance Methodologies**, **Open Source Intelligence (OSINT Hunter, Email Intelligence, Google Dorking)**, **Domain & Infrastructure Mapping (DNS Enumeration, Subdomain Brute-Forcing, WHOIS Trails)**, and **Artifact Analysis (Metadata Extraction, Website Fingerprinting)**.

---

## Lab Collection Index

### 1. Reconnaissance Foundations & OSINT Tradecraft
* **Red Team Fundamentals: Operator Zero**  
  *Lab Link:* [https://learn.secbyte.org/ctf/red-team-fundamentals-operator-zero](https://learn.secbyte.org/ctf/red-team-fundamentals-operator-zero)  
  *Focus:* Core principles of offensive engagements, phase breakdowns (Recon, Initial Access, Post-Exploitation), OPSEC considerations, and scoping boundaries.

* **Reconnaissance Basics: Mapping the Attack Surface**  
  *Lab Link:* [https://learn.secbyte.org/ctf/reconnaissance-basics-mapping-the-attack-surface](https://learn.secbyte.org/ctf/reconnaissance-basics-mapping-the-attack-surface)  
  *Focus:* Understanding target footprinting methodologies, balancing passive vs. active observation, and constructing initial target profiles.

* **Passive Recon Mastery**  
  *Lab Link:* [https://learn.secbyte.org/ctf/passive-recon-mastery](https://learn.secbyte.org/ctf/passive-recon-mastery)  
  *Focus:* Gathering target intelligence without sending direct traffic to victim assets using public registrars, search engine caches, Certificate Transparency (CT) logs, and archive databases.

* **Active Recon Operations**  
  *Lab Link:* [https://learn.secbyte.org/ctf/active-recon-operations](https://learn.secbyte.org/ctf/active-recon-operations)  
  *Focus:* Executing direct, stealthy interactions with target systems, managing request rates, utilizing proxies, and handling operational noise footprints.

* **OSINT Hunter**  
  *Lab Link:* [https://learn.secbyte.org/ctf/osint-hunter](https://learn.secbyte.org/ctf/osint-hunter)  
  *Focus:* Leveraging multi-source intelligence frameworks (Maltego, SpiderFoot, theHarvester), cross-referencing open web records, social media profiling, and target correlation.

### 2. Search Engines, Domain Intelligence & Subdomain Discovery
* **Google Dorking Lab: Discovery, Filtering & Validation**  
  *Lab Link:* [https://learn.secbyte.org/ctf/google-dorking-lab-discovery-filtering-validation](https://learn.secbyte.org/ctf/google-dorking-lab-discovery-filtering-validation)  
  *Focus:* Constructing advanced search operators (`site:`, `filetype:`, `inurl:`, `intitle:`) to locate exposed credentials, administrative portals, backup archives, and sensitive documents.

* **WHOIS Trail: Domain Intelligence Investigation**  
  *Lab Link:* [https://learn.secbyte.org/ctf/whois-trail-domain-intelligence-investigation](https://learn.secbyte.org/ctf/whois-trail-domain-intelligence-investigation)  
  *Focus:* Analyzing historical WHOIS record alterations, tracing domain ownership shifts, unmasking privacy proxy protection, and mapping organizational registrant emails.

* **DNS Enumeration: Mapping the Invisible**  
  *Lab Link:* [https://learn.secbyte.org/ctf/dns-enumeration-mapping-the-invisible](https://learn.secbyte.org/ctf/dns-enumeration-mapping-the-invisible)  
  *Focus:* Querying A, AAAA, MX, NS, TXT, and CNAME records, attempting DNS zone transfers (`axfr`), reverse DNS lookups, and detecting wildcard DNS configurations.

<Image src="image_agent_tag_17100581739682324516" alt="DNS query hierarchy showing recursive resolution and root/authoritative server responses" caption="DNS Query Hierarchy & Resolution Flow" />

---

* **Subdomain Discovery: Shadowstack Networks**  
  *Lab Link:* [https://learn.secbyte.org/ctf/subdomain-discovery-shadowstack-networks](https://learn.secbyte.org/ctf/subdomain-discovery-shadowstack-networks)  
  *Focus:* Uncovering unlinked subdomains using passive sources (crt.sh, SecurityTrails) and active brute-forcing (Amass, Sublist3r, Assetfinder, Subfinder).

### 3. Identity, Metadata & Web Fingerprinting
* **Email Intelligence Operations**  
  *Lab Link:* [https://learn.secbyte.org/ctf/email-intelligence-operations](https://learn.secbyte.org/ctf/email-intelligence-operations)  
  *Focus:* Harvest target corporate email syntax, verifying address validity without triggering alerts, checking breach databases (HaveIBeenPwned), and mapping employee hierarchy.

* **Metadata Extraction Lab**  
  *Lab Link:* [https://learn.secbyte.org/ctf/metadata-extraction-lab](https://learn.secbyte.org/ctf/metadata-extraction-lab)  
  *Focus:* Extracting hidden EXIF and document metadata from publicly hosted files (PDF, DOCX, JPG) using `exiftool` and `FOCA` to reveal internal usernames, software versions, and printer paths.

* **Website Fingerprinting: From Clues to Attribution**  
  *Lab Link:* [https://learn.secbyte.org/ctf/website-fingerprinting-from-clues-to-attribution](https://learn.secbyte.org/ctf/website-fingerprinting-from-clues-to-attribution)  
  *Focus:* Inspecting HTML source structures, tracking analytics/tracking IDs (Google Analytics, Facebook Pixel), analyzing CSS/JS dependencies, and attributing multiple domains to a single owner.

---

## Learning Path

### Path A: OSINT & Threat Intelligence Analyst
1. **Intelligence Fundamentals:** Start with [Reconnaissance Basics](https://learn.secbyte.org/ctf/reconnaissance-basics-mapping-the-attack-surface) and [Passive Recon Mastery](https://learn.secbyte.org/ctf/passive-recon-mastery).
2. **OSINT Frameworks:** Master intelligence tools in [OSINT Hunter](https://learn.secbyte.org/ctf/osint-hunter), [Email Intelligence Operations](https://learn.secbyte.org/ctf/email-intelligence-operations), [Google Dorking Lab](https://learn.secbyte.org/ctf/google-dorking-lab-discovery-filtering-validation), and [WHOIS Trail](https://learn.secbyte.org/ctf/whois-trail-domain-intelligence-investigation).

### Path B: Infrastructure Mapping Specialist
1. **DNS & Subdomains:** Map domain assets via [DNS Enumeration](https://learn.secbyte.org/ctf/dns-enumeration-mapping-the-invisible) and [Subdomain Discovery](https://learn.secbyte.org/ctf/subdomain-discovery-shadowstack-networks).
2. **Active Recon:** Transition to active probing using [Active Recon Operations](https://learn.secbyte.org/ctf/active-recon-operations).

### Path C: Web & Artifact Forensics Specialist
1. **Metadata & Attribution:** Extract hidden intelligence from web targets via [Metadata Extraction Lab](https://learn.secbyte.org/ctf/metadata-extraction-lab) and [Website Fingerprinting](https://learn.secbyte.org/ctf/website-fingerprinting-from-clues-to-attribution).

---

## How to Use the Labs

1. Select a practice scenario from the **Lab Collection Index**.
2. Click the corresponding link to open the exercise environment on Learn SecByte.
3. Review scenario directives, target corporate names, domains, or document repositories.
4. Execute Google Dorks, query DNS servers, analyze document metadata, perform certificate log searches, or correlate analytics IDs to capture flags.

---

## Target Audience

* **Red Team Operators & Ethical Hackers:** Build stealthy footprinting workflows, enumerate hidden subdomains, and gather target intelligence without raising alarm.
* **Threat Intelligence Analysts:** Track adversary infrastructure, analyze WHOIS records, and perform cross-domain attribution using web tracking IDs.
* **OSINT Investigators:** Master Google Dorking techniques, metadata extraction, and breach database correlation.
* **Cybersecurity Students:** Acquire practical experience in non-intrusive reconnaissance, DNS queries, and attack surface mapping.

---

## Disclaimer

All lab links in this repository lead to official training environments hosted on Learn SecByte. All materials and exercises are provided strictly for educational purposes, defensive skill building, and authorized security research. Unauthorized scanning or scraping against external targets is strictly prohibited.
