# 🕵️ Pip-Intel - Comprehensive OSINT & Cyber Intelligence Tool

[![GitHub](https://img.shields.io/badge/GitHub-sobri3195-blue?style=flat-square&logo=github)](https://github.com/sobri3195)
[![License](https://img.shields.io/badge/License-MIT-green.svg?style=flat-square)](LICENSE)
[![Platform](https://img.shields.io/badge/Platform-Linux-orange?style=flat-square&logo=linux)](https://www.linux.org/)

## 📋 Overview

**Pip-Intel** is a powerful and comprehensive tool designed for OSINT (Open Source Intelligence) and cyber intelligence gathering activities. It consolidates various open-source tools into a single user-friendly interface, simplifying the data collection and analysis processes for researchers and cybersecurity professionals.

This tool utilizes Python-written pip packages to gather information from various data points, equipped with the capability to collect detailed information through email addresses, phone numbers, IP addresses, and social media accounts.

---

## 👨‍⚕️ Author Information

**Modified & Enhanced By:**  
**Lettu Kes dr. Muhammad Sobri Maulana, S.Kom, CEH, OSCP, OSCE**

### 📧 Contact Information
- **Email:** [muhammadsobrimaulana31@gmail.com](mailto:muhammadsobrimaulana31@gmail.com)
- **GitHub:** [github.com/sobri3195](https://github.com/sobri3195)

### 🌐 Social Media & Online Presence

<div align="left">

| Platform | Link |
|----------|------|
| 🎥 **YouTube** | [Muhammad Sobri Maulana](https://www.youtube.com/@muhammadsobrimaulana6013) |
| 📱 **TikTok** | [@dr.sobri](https://www.tiktok.com/@dr.sobri) |
| 💬 **Telegram** | [winlin_exploit](https://t.me/winlin_exploit) |
| 🌐 **Website** | [muhammadsobrimaulana.netlify.app](https://muhammadsobrimaulana.netlify.app) |
| 🚀 **Sevalla** | [muhammad-sobri-maulana](https://muhammad-sobri-maulana-kvr6a.sevalla.page/) |
| 💬 **WhatsApp Group** | [Join Community](https://chat.whatsapp.com/B8nwRZOBMo64GjTwdXV8Bl) |

</div>

---

## 💖 Support & Donation

If you find this tool useful, please consider supporting the development and maintenance through any of the following platforms:

<div align="left">

| Platform | Link |
|----------|------|
| 💳 **Lynk.id** | [muhsobrimaulana](https://lynk.id/muhsobrimaulana) |
| ☕ **Trakteer** | [Support Here](https://trakteer.id/g9mkave5gauns962u07t) |
| 🛍️ **Gumroad** | [maulanasobri](https://maulanasobri.gumroad.com/) |
| 🎨 **KaryaKarsa** | [muhammadsobrimaulana](https://karyakarsa.com/muhammadsobrimaulana) |
| 💰 **Nyawer** | [MuhammadSobriMaulana](https://nyawer.co/MuhammadSobriMaulana) |

</div>

Your support helps maintain and improve this project! 🙏

---

## 🚀 Features

Pip-Intel offers a wide range of functionalities including:

### 📧 Email-Based Account Lookup
- **Email to Registered Accounts** - Discover which platforms an email is registered on
- **Gravatar Account Finder** - Find Gravatar accounts associated with an email
- **Email Address Enumeration** - Enumerate email addresses from specified domains

### 📱 Phone Number-Based OSINT
- **Phone Number Lookup** - Search for accounts registered with a phone number
- **Multi-platform Detection** - Check phone number usage across various platforms

### 🌍 IP Geolocation and Mapping
- **IP Geolocator** - Locate and map IP addresses with coordinate visualization
- **Public IP Detection** - Retrieve your current public IP address information

### 👥 Deep Social Media and User Analysis
- **Social Media Analyzer** - Comprehensive social media profile analysis
- **Gravatar Information Display** - Detailed Gravatar account information
- **Mastodon OSINT** - Intelligence gathering on Mastodon users
- **Advanced Username Search** - Deep search across multiple platforms
- **Simple User Search** - Quick username lookups

### 🕸️ Dark Web Intelligence
- **OnionSearch** - Search and scrape .onion domains
- **TheDevilsEye** - Hidden services discovery and analysis

### 🔍 Web Intelligence
- **Web Information Gathering** - Lightweight reconnaissance tool
- **Subdomain Enumeration** - Discover subdomains of target domains
- **Arachnid Spider** - Find sensitive data and leaks
- **Photon Crawler** - Fast OSINT web crawler
- **Postman Data Search** - Search for sensitive data in Postman
- **Credentials Extraction** - Extract tokens, credentials from Postman
- **Google Dorking** - Advanced Google search queries

---

## 📦 Installation

### Prerequisites
- Linux-based operating system (Ubuntu/Debian/Kali recommended)
- Python 3.x
- pip3
- sudo privileges

### Quick Install

```bash
# Clone the repository
git clone https://github.com/sobri3195/pegasus-pip-intel.git
cd pegasus-pip-intel

# Make the script executable
chmod +x pegasus-pip-intel.sh

# Run the installer (Option 21 in the menu)
./pegasus-pip-intel.sh
# Select option 21 to install all required tools
```

### Manual Installation of Tools

```bash
# Update system
sudo apt-get update

# Install pip packages
sudo pip3 install maigret
sudo pip3 install ignorant
sudo pip3 install holehe
sudo pip3 install social-analyzer
sudo pip3 install orbis-unum
sudo pip3 install arachnid-spider
sudo pip3 install masto
sudo pip3 install postmaniac
sudo pip3 install ipinfo
sudo pip3 install thedevilseye
sudo pip3 install R3con1z3r
sudo pip3 install oxdork
sudo pip3 install hashtray
sudo pip3 install postleaks
sudo pip3 install onionsearch
sudo pip3 install search4
sudo pip3 install bbot

# Install apt packages
sudo apt install assetfinder -y
sudo apt install photon -y
sudo apt install tor -y
sudo apt install curl -y
```

---

## 🎯 Usage

### Running the Tool

```bash
./pegasus-pip-intel.sh
```

### Main Menu Options

The tool presents an interactive menu with the following categories:

1. **Email-Based Account Lookup** (Options 1-3)
2. **Phone Number-Based OSINT** (Option 4)
3. **IP Geolocation and Mapping** (Options 5-6)
4. **Deep Social Media and User Analysis** (Options 7-11)
5. **Dark Web** (Options 12-13)
6. **Web Intelligence** (Options 14-20)
7. **Install** (Option 21)
8. **System Info** (Option 22)
9. **Exit** (Option 99)
10. **About** (Option 0)

### Example Usage

#### Email OSINT
```bash
# Select option 1
Enter target email address: target@example.com
```

#### Username Search
```bash
# Select option 10 for advanced search
Enter Target Username: johndoe
```

#### IP Geolocation
```bash
# Select option 5
Enter IP Address: 8.8.8.8
```

---

## 🔧 Tools Integrated

| Tool | Description |
|------|-------------|
| **Holehe** | Check if email is used on different sites |
| **Hashtray** | OSINT tool for Gravatar accounts |
| **BBOT** | Recursive Internet Scanner |
| **Ignorant** | Check phone number usage on sites |
| **Orbis-Enum** | IP geolocation visualization tool |
| **Social-Analyzer** | Social media profile analysis |
| **Maigret** | Username search across multiple sites |
| **Search4** | Fast people finder tool |
| **OnionSearch** | Dark web .onion search engine scraper |
| **TheDevilsEye** | Ahmia.fi based hidden service finder |
| **R3con1z3r** | Web information gathering tool |
| **Assetfinder** | Fast subdomain enumeration |
| **Arachnid-spider** | OSINT web crawler for sensitive data |
| **Photon** | Fast OSINT crawler |
| **Postleaks** | Search Postman public library |
| **Postmaniac** | Extract credentials from Postman |
| **Oxdork** | Google Dorking tool |

---

## ⚠️ Legal Disclaimer

**IMPORTANT: Please Read Carefully**

This tool is provided for **educational and research purposes only**. Users must comply with all applicable laws and regulations in their jurisdiction.

### Acceptable Use:
- Security research with proper authorization
- Educational purposes in controlled environments
- Penetration testing with written permission
- Legal OSINT investigations

### Prohibited Use:
- Unauthorized access to computer systems
- Harassment or stalking of individuals
- Any illegal activities
- Violation of privacy laws

**By using this tool, you agree to use it responsibly and legally. The author is not responsible for any misuse or damage caused by this tool.**

---

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

### How to Contribute:
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

---

## 🙏 Acknowledgments

- Original Author: **EmreKybs** (BloodBane)
- Modified & Enhanced By: **Lettu Kes dr. Muhammad Sobri Maulana, S.Kom, CEH, OSCP, OSCE**
- All the developers of the integrated OSINT tools
- The cybersecurity and OSINT community

---

## 📞 Support & Community

### Get Help:
- **WhatsApp Group:** [Join Community](https://chat.whatsapp.com/B8nwRZOBMo64GjTwdXV8Bl)
- **Telegram:** [winlin_exploit](https://t.me/winlin_exploit)
- **Email:** [muhammadsobrimaulana31@gmail.com](mailto:muhammadsobrimaulana31@gmail.com)

### Stay Updated:
- **YouTube:** [Muhammad Sobri Maulana Channel](https://www.youtube.com/@muhammadsobrimaulana6013)
- **TikTok:** [@dr.sobri](https://www.tiktok.com/@dr.sobri)
- **Website:** [muhammadsobrimaulana.netlify.app](https://muhammadsobrimaulana.netlify.app)

---

## 🌟 Show Your Support

If you find this project useful, please consider:
- ⭐ Starring this repository
- 🍴 Forking the project
- 💖 Supporting through donation platforms listed above
- 📢 Sharing with others

---

<div align="center">

**Made with ❤️ for the Cybersecurity Community**

[![GitHub](https://img.shields.io/badge/Follow-sobri3195-blue?style=social&logo=github)](https://github.com/sobri3195)

</div>
