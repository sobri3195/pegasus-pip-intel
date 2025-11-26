# Changelog - Pegasus Pip-Intel

## [Version 2.0] - 10 New Features Added

### New Features

This release adds 10 powerful new OSINT features to enhance intelligence gathering capabilities:

#### Web Intelligence Enhancements (Options 23-27)
1. **Option 23 - WHOIS Domain Lookup**
   - Tool: WHOIS
   - Functionality: Retrieve domain registration and ownership information
   - Usage: Domain reconnaissance and ownership tracking

2. **Option 24 - Wayback Machine URL History**
   - Tool: waybackurls
   - Functionality: Fetch historical URLs from the Wayback Machine
   - Usage: Discover old/deleted pages and content

3. **Option 25 - DNS Reconnaissance**
   - Tool: dnsrecon
   - Functionality: Advanced DNS enumeration and analysis
   - Usage: DNS record discovery, zone transfers, reverse lookups

4. **Option 26 - Advanced Subdomain Finder**
   - Tool: subfinder
   - Functionality: Fast passive subdomain discovery with multiple sources
   - Usage: Comprehensive subdomain enumeration

5. **Option 27 - Web Technologies Detection**
   - Tool: whatweb
   - Functionality: Identify CMS, frameworks, plugins, and web technologies
   - Usage: Technology stack fingerprinting

#### GitHub & Platform OSINT (Options 28-30)
6. **Option 28 - GitHub User Intelligence**
   - Tool: gitfive
   - Functionality: Gather intelligence on GitHub users and repositories
   - Usage: GitHub account investigation and code analysis

7. **Option 29 - Twitter/X Username OSINT**
   - Tool: twint
   - Functionality: Advanced Twitter scraping without API
   - Usage: Twitter profile and activity analysis

8. **Option 30 - LinkedIn Profile Finder**
   - Tool: linkedin2username
   - Functionality: Generate username lists from company profiles
   - Usage: Corporate intelligence and employee enumeration

#### Breach & Leak Detection (Options 31-32)
9. **Option 31 - Email Breach Checker**
   - Tool: h8mail
   - Functionality: Find compromised credentials in data breaches
   - Usage: Email security assessment and breach notification

10. **Option 32 - Sherlock Username Tracker**
    - Tool: sherlock
    - Functionality: Hunt down usernames across social networks
    - Usage: Cross-platform username discovery

### Installation Updates

#### New Python Packages
- h8mail
- twint
- gitfive
- linkedin2username

#### New APT Packages
- whois
- dnsrecon
- whatweb

#### New Go-based Tools
- subfinder (github.com/projectdiscovery/subfinder/v2/cmd/subfinder@latest)
- waybackurls (github.com/tomnomnom/waybackurls@latest)
- sherlock (github.com/sherlock-project/sherlock@latest)

### Documentation Updates
- Updated README.md with all new features
- Added new feature categories in menu
- Updated tool integration table
- Enhanced installation prerequisites (added Go requirement)

### Menu Organization
Features are now organized into 8 categories:
1. Email-Based Account Lookup
2. Phone Number-Based OSINT
3. IP Geolocation and Mapping
4. Deep Social Media and User Analysis
5. Dark Web
6. Web Intelligence (expanded)
7. GitHub & Platform OSINT (new category)
8. Breach & Leak Detection (new category)

### Technical Improvements
- Maintained consistent code style and color scheme
- Added proper error handling for new tools
- Integrated Go tools with PATH configuration
- Updated automated installation script (Option 21)

---

## Enhanced Capabilities

With these 10 new features, Pegasus Pip-Intel now offers:
- **32 total OSINT features**
- **27 integrated tools**
- **Comprehensive coverage** across email, phone, social media, web, GitHub, and breach detection
- **Multi-language support** (Python, Go, system tools)

---

**Modified By:** Lettu Kes dr. Muhammad Sobri Maulana, S.Kom, CEH, OSCP, OSCE  
**Date:** 2024  
**License:** MIT
