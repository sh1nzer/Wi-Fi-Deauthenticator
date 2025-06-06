# Wi-Fi Deauthentication Tool

### 🚀 Recreated in Python as a personal project by **Shaurya Singh**
⚠️ Educational and ethical use only. Originally inspired by [ezhil56x/deauther](https://github.com/ezhil56x/deauther)

---

## ⚠️ Disclaimer

This tool is provided **strictly for educational and ethical penetration testing** purposes. Unauthorized use of this tool on networks or devices you do not own or have explicit permission to test is **illegal** and may lead to serious legal consequences.

By using this tool, you agree to:

- Use it **only on networks you own or are authorized to test**.
- Comply with all local, national, and international cybersecurity laws.
- Take full responsibility for your actions while using this tool.

The creator, **Shaurya Singh**, shall not be held liable for any misuse or resulting damages.

---

## 📘 Introduction

The **Wi-Fi Deauthentication Tool** is a command-line utility built for Linux systems to simulate deauthentication attacks for **educational** and **penetration testing training**. It leverages the `aircrack-ng` suite to scan, monitor, and disconnect clients from Wi-Fi networks.

> ⚠️ **Note:** This tool is built for cybersecurity learners, researchers, and ethical hackers to **understand Wi-Fi vulnerabilities** in a controlled environment.

---

## 🧰 Features

- 🔍 **Scan Nearby Wi-Fi Networks**  
- 🎯 **Select Specific Networks for Attack Simulation**
- ❌ **Deauthenticate a Targeted Client**
- 🚫 **Deauthenticate All Clients from a Network**
- 🖥️ **Check Wi-Fi Adapter Status**
- 🔁 **Change Wi-Fi Interface Name**

---

## 🧱 Prerequisites

- Linux OS
- Root access (`sudo`)
- Wi-Fi adapter that supports monitor mode and packet injection
- Installed tools:
  - `aircrack-ng`
  - `airodump-ng`
  - `aireplay-ng`

### 🛠️ Install Aircrack-ng

For Debian-based systems:

sudo apt-get install aircrack-ng

2. Once the aircrack-ng package is installed, airodump-ng and aireplay-ng should be available in your system.

## Usage

1. Clone the repository or download the script.
2. Ensure that the script has executable permissions (`chmod +x wifideauth.sh`).
3. Run the script using `sudo ./wifideauth.sh`.
4. Follow the on-screen menu prompts to choose the desired actions.

Please note that unauthorized attacks on devices that you do not own or do not have permission to test are illegal and unethical. Performing such attacks can lead to severe consequences, including legal actions, criminal charges, and penalties. The author of this tool shall not be held responsible for any damages or liabilities caused by the use or misuse of this tool. Always ensure that you have proper authorization and legal permissions before using this tool. Use it responsibly, respect privacy and security, and comply with all applicable laws and regulations.

**IMPORTANT:** This tool comes with no guarantees or warranties. The author will not be responsible for any consequences resulting from the use or misuse of this tool. Use it responsibly and at your own risk.
