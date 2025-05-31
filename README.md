# CmdPhishHackPro
# CmdPhishHackPro (Modified PyPhisher v2.1.8)

![License](https://img.shields.io/badge/license-MIT-green)
![Platform](https://img.shields.io/badge/platform-Termux%20%7C%20Linux-blue)
![Python](https://img.shields.io/badge/python-3.x-yellow)

CmdPhishHackPro is an advanced phishing tool modified from PyPhisher. It provides phishing templates for 70+ websites including Facebook, Instagram, and GitHub.

> ⚠️ For **educational use** and **authorized testing** only.

## Features
- 70+ phishing templates
- Auto-generated social engineering links
- Cloudflared, portforwarding & LocalXpose tunneling support
- OTP phishing support
- Data logging and email alert options
- Termux and Linux compatible

## Requirements

- Python 3.x
- Termux or Linux
- PHP, SSH, Proot (Termux only)
- Python modules:
  - requests
  - beautifulsoup4
  - rich

## Installation on Termux

```bash
pkg update && pkg upgrade
pkg install git python php openssh proot -y
git clone https://gitlab.com/Comradehacker1120/CmdPhishHackPro 
cd CmdPhishHackPro 
termux-setup-storage
pip3 install -r requirements.txt 
python CmdPhishHackPro.py
