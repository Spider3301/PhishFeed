# PhishFeed 🛡️  
**Intelligence-Driven Real-Time Phishing URL Feed**

![Status](https://img.shields.io/badge/Status-Active-brightgreen)
![License](https://img.shields.io/badge/License-MIT-blue)
![Threat-Intel](https://img.shields.io/badge/Category-Threat%20Intelligence-red)
![OSINT](https://img.shields.io/badge/OSINT-Enabled-orange)

PhishFeed is an **intelligence-based phishing detection feed** that continuously collects, analyzes, and publishes phishing URLs gathered from **open-source platforms, directory listings, and search-engine indexed pages**.  
Fast, lightweight, and built for defenders.

---

## 🚀 Features

- **Real-time phishing URL discovery**
- **OSINT-driven collection** from multiple open data sources
- **Automated classification & filtering**
- **Continuously updated public feed**
- Ideal for **SOC teams, threat intel platforms, firewalls, SIEMs, and researchers**

---

## 🧭 How It Works

1. **Collection**  
   Gathers URLs from OSINT sources, open directories, search-engine indexes, and community threat repositories.

2. **Identification**  
   Identifies phishing URLs using pattern analysis, heuristics, and automated filtering logic.

3. **Publishing**  
   Cleansed & validated phishing URLs are dumped into this repo in near-real time.

4. **Consumption**  
   Anyone can clone, pull, integrate, or automate this feed into their security stack.

---

## 📂 Repository Contents

- **`domains.txt`** → Main feed of phishing URLs  
- **Automation scripts (coming soon)**  
- **Documentation**

This feed updates frequently to maintain fresh and active phishing indicators.

---

## ⚙️ Usage

### Clone & Inspect
```bash
git clone https://github.com/Spider3301/PhishFeed.git
cd PhishFeed
less domains.txt
