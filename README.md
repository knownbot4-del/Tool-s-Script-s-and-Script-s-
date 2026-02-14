
# 🛡️ Network & Port Scanner 

A professional-grade network radar and port scanner with **Multi-threading** and **Vulnerability Detection**. Reports findings directly to Discord.

## 🚀 Features
* **Network Radar:** Scans the local network for active devices.
* **Turbo Port Scan:** Scans ports 1-500 in seconds using `ThreadPoolExecutor`.
* **Vuln Check:** Identifies banners (like `vsFTPd 2.3.4`) and flags known threats.
* **Discord Integration:** Real-time alerts via Webhooks.

### 🛠️ Planned for Version 3 [V3]
- [ ] Advanced Banner Grabbing (HTTP, SSH, MySQL probes).
- [ ] Expand VULN_DB to 30+ known software vulnerabilities.
- [ ] Automated OS Detection (Fingerprinting).
- [ ] JSON logging for professional reporting.

## 🛠️ Setup & Usage
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/knownbot4-del/Network-Scanner-.git](https://github.com/knownbot4-del/Network-Scanner-.git)
   cd Network-Scanner-

2. **Create config.py in root dir :**
   ```Python
   DISCORD_WEBHOOK = "YOUR_DISCORD_URL_HERE"

3. **Install dependencies**
   ```basj
   pip install requests

4. **Run the scanner**
   ```bash
   python scanner.py


**[!] Note: This tool is for educational purposes only. Use it responsibly.**
   
