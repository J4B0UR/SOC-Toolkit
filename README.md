# SOC Toolkit

SOC Toolkit is a free, open-source browser extension designed to streamline security investigations by eliminating the need for constant copying and pasting during incident analysis. Compatible with Chromium-based browsers (Chrome, Edge, Brave, Opera) and Firefox.

![GitHub stars](https://img.shields.io/github/stars/username/soctoolkit?style=social)
![GitHub license](https://img.shields.io/github/license/username/soctoolkit)
![Chrome Web Store](https://img.shields.io/chrome-web-store/rating/extensionid)
![Firefox Add-ons](https://img.shields.io/amo/rating/soctoolkit)

## 🔍 Overview

SOC Toolkit empowers security analysts to perform rapid IOC (Indicators of Compromise) queries and manage investigation artifacts directly within the browser. Simply select text, right-click, and choose the desired investigation method from the context menu.

![Screenshot of SOC Toolkit in action](screenshot.png)

## ✨ Features

### Fast IOC Lookups
- **IP Reputation** via VirusTotal, AbuseIPDB, GreyNoise, IBM X-Force, Talos, and more
- **WHOIS for IP/Domain** 
- **Hash Analysis** (MD5, SHA1, SHA256) across multiple sources
- **Domain Intelligence** via AlienVault OTX, VirusTotal, and others
- **Blockchain Address Verification**
- **MAC Address Manufacturer Identification**
- **User-Agent Parsing**
- **CVE Information Lookup**
- **Microsoft Error Code Reference**
- **Windows Event ID Lookup** (Windows, SharePoint, SQL Server, Exchange, Sysmon)
- **Windows Binary Verification** via Winbindex
- **LOLBins Check** (Living Off The Land Binaries)
- **Data Decoding** via CyberChef (Base64, HEX, etc)

### Advanced Investigation Tools
- **Query History**: Store previous searches for quick reference
- **Investigation Cases**: Organize queries by case to maintain context
- **Report Export**: Export results in various formats (CSV, JSON)
- **Custom Interface**: Personalize with light/dark theme
- **Text Highlighting**: Emphasize specific terms on web pages with type-specific styling
- **Integrated Notes**: Attach notes to specific IOCs
- **IOC Correlation**: Visualize relationships between different indicators
- **Timeline Feature**: Track investigation activities chronologically

## 🔄 Latest Features

- **Modern UI**: Clean, responsive design with gradient backgrounds and improved card layouts
- **Enhanced Text Highlighting**: Type-specific styling and improved tooltips
- **Optimized Performance**: Faster loading and reduced memory consumption
- **Improved Dark Theme**: Better contrast and readability
- **Advanced IOC Pattern Recognition**: Better detection and visualization
- **Streamlined Workflow**: Organized by investigation cases

## 🚀 Installation

### Chrome, Edge, Brave, and other Chromium-based browsers
1. Visit the [Chrome Web Store](https://chrome.google.com/webstore/)
2. Search for "SOC Toolkit" or navigate directly using the link
3. Click "Add to Chrome"

### Firefox
1. Visit the [Firefox Add-ons Store](https://addons.mozilla.org/)
2. Search for "SOC Toolkit" or navigate directly using the link
3. Click "Add to Firefox"

## 💡 Usage Guide

1. Select any text (IP, domain, hash, etc.) on any web page
2. Right-click the selection
3. Navigate to the SOC Toolkit context menu
4. Choose the desired analysis type
5. A new tab will open with the results

### Usage Examples
- **IPs**: 8.8.8.8, 1.1.1.1
- **Domains**: example.com, github.com
- **Hashes**: 44d88612fea8a8f36de82e1278abb02f
- **CVEs**: CVE-2021-44228
- **Event IDs**: 4624, 4625
- **Error Codes**: 0x80004005

### Advanced Features

- **Search History**: Access history by clicking the extension icon
- **Investigation Mode**: Create "cases" to group related IOCs
- **Text Highlighting**: Use the context menu to highlight important terms on pages
- **Timeline View**: Track and organize investigation activities chronologically

## 📜 License

Distributed under the MIT License. See `LICENSE` for more information.

## 🙏 Acknowledgments

- [VirusTotal](https://www.virustotal.com/)
- [AbuseIPDB](https://www.abuseipdb.com/)
- [AlienVault OTX](https://otx.alienvault.com/)
- [CyberChef](https://cyberchef.org/)
- [LOLBAS Project](https://lolbas-project.github.io/)
- [Winbindex](https://winbindex.m417z.com/)
- All other integrated platforms and tools

## 🔮 Future Features

- REST API integration for programmatic access
- MISP and STIX/TAXII integration for IOC export
- Integration with ticketing systems (JIRA, ServiceNow)
- Advanced visual correlation of IOCs
- Organization-specific intel source customization
- Automated IOC extraction from web pages
- Advanced regex-based IOC detection in text
- Multi-language support
- AI-powered IOC contextual analysis
- Enhanced reporting capabilities
- Collaborative investigation features

---

<div align="center">

Developed by [Gabriel Jabour](https://www.linkedin.com/in/gjabour/) 

</div> 