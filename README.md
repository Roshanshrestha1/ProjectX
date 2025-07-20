# 🎭 PhantomPhisherX - Advanced Phishing Simulation Tool

<div align="center">

![PhantomPhisherX Banner](https://img.shields.io/badge/PhantomPhisherX-Advanced%20Phishing%20Simulation-blue?style=for-the-badge&logo=security)
![Version](https://img.shields.io/badge/Version-3.0.0-green?style=for-the-badge)
![License](https://img.shields.io/badge/License-GPL--3.0-red?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-Linux%20%7C%20Windows%20%7C%20macOS-orange?style=for-the-badge)

**Advanced Phishing Simulation Tool for Educational Purposes**

[![GitHub stars](https://img.shields.io/github/stars/Roshanshrestha1/PhantomPhisherX?style=social)](https://github.com/Roshanshrestha1/PhantomPhisherX/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/Roshanshrestha1/PhantomPhisherX?style=social)](https://github.com/Roshanshrestha1/PhantomPhisherX/network)
[![GitHub issues](https://img.shields.io/github/issues/Roshanshrestha1/PhantomPhisherX)](https://github.com/Roshanshrestha1/PhantomPhisherX/issues)
[![GitHub pull requests](https://img.shields.io/github/issues-pr/Roshanshrestha1/PhantomPhisherX)](https://github.com/Roshanshrestha1/PhantomPhisherX/pulls)

</div>

---

## 📋 Table of Contents

- [🎯 Overview](#-overview)
- [✨ Features](#-features)
- [🚀 Installation](#-installation)
- [📖 Usage](#-usage)
- [🎨 Supported Platforms](#-supported-platforms)
- [🔧 Configuration](#-configuration)
- [📊 Screenshots](#-screenshots)
- [🛠️ Troubleshooting](#️-troubleshooting)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)
- [⚠️ Disclaimer](#️-disclaimer)

---

## 🎯 Overview

**PhantomPhisherX** is a cutting-edge phishing simulation tool designed for educational purposes and cybersecurity awareness training. It provides a comprehensive platform for understanding how phishing attacks work, helping organizations and individuals improve their security posture through realistic simulations.

### 🎭 What Makes PhantomPhisherX Special?

- **🎯 Realistic Templates**: 30+ authentic-looking phishing pages
- **🌐 Multiple Tunneling**: Cloudflared, Ngrok, LocalXpose support
- **🔒 Advanced Security**: Anti-detection and browser simulation
- **📱 Cross-Platform**: Works on Linux, Windows, and macOS
- **🎨 Modern UI**: Beautiful, intuitive user interface
- **📊 Analytics**: Real-time credential capture and IP tracking

---

## ✨ Features

### 🎨 **Advanced Templates**
- **Social Media**: Instagram, Facebook, Twitter, Snapchat
- **Email Services**: Gmail, Yahoo, ProtonMail
- **Gaming**: Steam, Origin, PlayStation, Xbox
- **Business**: LinkedIn, Microsoft, GitHub, GitLab
- **Entertainment**: Netflix, Spotify, Twitch, Reddit
- **Custom Templates**: Create your own phishing pages

### 🌐 **Tunneling Services**
- **Cloudflared** ⭐ (Recommended)
- **Ngrok.io** (Alternative)
- **LocalXpose** (New!)
- **Localhost** (For Development)

### 🔒 **Security Features**
- **Anti-Detection**: Advanced browser fingerprinting evasion
- **Real-time Validation**: Instant credential verification
- **IP Tracking**: Comprehensive victim analytics
- **URL Masking**: Professional URL shortening and masking
- **Browser Simulation**: Realistic user behavior patterns

### 📊 **Analytics & Reporting**
- **Credential Capture**: Real-time username/password logging
- **IP Address Tracking**: Victim location and device info
- **User Agent Analysis**: Browser and OS detection
- **Timestamp Logging**: Detailed activity timestamps
- **Export Options**: Multiple format support

---

## 🚀 Installation

### 📋 Prerequisites

```bash
# Required packages
- PHP (7.4 or higher)
- cURL
- Git
- Bash shell
```

### 🔧 Quick Installation

```bash
# Clone the repository
git clone https://github.com/Roshanshrestha1/PhantomPhisherX.git

# Navigate to directory
cd PhantomPhisherX

# Make executable
chmod +x phantomphisherx.sh

# Run the tool
./phantomphisherx.sh
```

### 🐧 Linux Installation

```bash
# Ubuntu/Debian
sudo apt update
sudo apt install php curl git

# CentOS/RHEL
sudo yum install php curl git

# Arch Linux
sudo pacman -S php curl git
```

### 🪟 Windows Installation

```bash
# Using WSL (Recommended)
wsl --install
wsl
# Then follow Linux installation

# Using Git Bash
# Download and install Git for Windows
# Then follow the Quick Installation steps
```

### 🍎 macOS Installation

```bash
# Using Homebrew
brew install php curl git

# Then follow the Quick Installation steps
```

---

## 📖 Usage

### 🎯 Basic Usage

```bash
# Start the tool
./phantomphisherx.sh

# Follow the interactive menu:
# 1. Select "Website Attack"
# 2. Choose your target platform
# 3. Select tunneling service
# 4. Share the generated link
```

### 🎨 Advanced Usage

#### Custom Template Creation
```bash
# Create custom template
1. Navigate to .sites/ directory
2. Create new folder for your template
3. Add login.html and login.php files
4. Customize the design and functionality
```

#### URL Masking
```bash
# Enable URL masking
1. Select "Custom" option
2. Enter your target URL
3. Choose masking option
4. Get masked URL for distribution
```

### 📊 Monitoring Results

```bash
# View captured credentials
cat auth/usernames.txt

# View IP addresses
cat auth/ip.txt

# View detailed logs
cat auth/url_info.txt
```

---

## 🎨 Supported Platforms

### 📱 **Social Media**
| Platform | Status | Features |
|----------|--------|----------|
| Instagram | ✅ Active | Login, Signup, Followers |
| Facebook | ✅ Active | Login, Security, Messenger |
| Twitter | ✅ Active | Login, Signup |
| Snapchat | ✅ Active | Login, Signup |
| LinkedIn | ✅ Active | Login, Professional |

### 📧 **Email Services**
| Platform | Status | Features |
|----------|--------|----------|
| Gmail | ✅ Active | Login, Signup |
| Yahoo | ✅ Active | Login, Mobile |
| ProtonMail | ✅ Active | Login, Security |

### 🎮 **Gaming Platforms**
| Platform | Status | Features |
|----------|--------|----------|
| Steam | ✅ Active | Login, Store |
| Origin | ✅ Active | Login, Games |
| PlayStation | ✅ Active | Login, Network |
| Xbox | ✅ Active | Login, Live |

### 💼 **Business Tools**
| Platform | Status | Features |
|----------|--------|----------|
| GitHub | ✅ Active | Login, Repositories |
| GitLab | ✅ Active | Login, Projects |
| Microsoft | ✅ Active | Login, Office |
| WordPress | ✅ Active | Login, Admin |

### 🎬 **Entertainment**
| Platform | Status | Features |
|----------|--------|----------|
| Netflix | ✅ Active | Login, Streaming |
| Spotify | ✅ Active | Login, Music |
| Twitch | ✅ Active | Login, Gaming |
| Reddit | ✅ Active | Login, Communities |

---

## 🔧 Configuration

### ⚙️ Environment Variables

```bash
# Server Configuration
HOST="127.0.0.1"
PORT="8080"

# Tunneling Configuration
CLOUDFLARED_PATH=".server/cloudflared"
NGROK_PATH=".server/ngrok"

# Logging Configuration
LOG_DIR="auth/"
CREDENTIALS_FILE="usernames.txt"
IP_FILE="ip.txt"
```

### 🎨 Customization

#### Theme Customization
```bash
# Edit color scheme in phantomphisherx.sh
GREEN="\033[1;32m"
RED="\033[1;31m"
BLUE="\033[1;34m"
CYAN="\033[1;36m"
```

#### Template Customization
```bash
# Add custom templates
.sites/
├── your_template/
│   ├── login.html
│   ├── login.php
│   └── assets/
```

---

## 📊 Screenshots

<div align="center">

### 🎭 Main Interface
![Main Menu](https://i.imgur.com/example1.png)

### 🌐 Site Selection
![Site Selection](https://i.imgur.com/example2.png)

### 🔗 Tunnel Configuration
![Tunnel Menu](https://i.imgur.com/example3.png)

### 📊 Results Dashboard
![Results](https://i.imgur.com/example4.png)

</div>

---

## 🛠️ Troubleshooting

### ❌ Common Issues

#### Issue: Menu Loop
```bash
# Solution: Clear terminal and restart
clear
./phantomphisherx.sh
```

#### Issue: PHP Server Not Starting
```bash
# Check PHP installation
php --version

# Install PHP if missing
sudo apt install php  # Ubuntu/Debian
```

#### Issue: Tunnel Not Working
```bash
# Check internet connection
ping google.com

# Try different tunneling service
# Use Cloudflared (recommended)
```

#### Issue: Permission Denied
```bash
# Fix permissions
chmod +x phantomphisherx.sh
chmod -R 755 .sites/
```

### 🔧 Advanced Troubleshooting

#### Debug Mode
```bash
# Enable debug logging
export DEBUG=1
./phantomphisherx.sh
```

#### Manual Tunnel Setup
```bash
# Manual Cloudflared setup
./.server/cloudflared tunnel --url http://127.0.0.1:8080
```

---

## 🤝 Contributing

We welcome contributions! Here's how you can help:

### 🐛 Bug Reports
1. Check existing issues
2. Create new issue with detailed description
3. Include error logs and system info

### 💡 Feature Requests
1. Describe the feature clearly
2. Explain the use case
3. Provide mockups if possible

### 🔧 Code Contributions
1. Fork the repository
2. Create feature branch
3. Make your changes
4. Test thoroughly
5. Submit pull request

### 📝 Code Style
```bash
# Follow these guidelines:
- Use meaningful variable names
- Add comments for complex logic
- Follow bash scripting best practices
- Test on multiple platforms
```

---

## 📄 License

This project is licensed under the **GNU General Public License v3.0** - see the [LICENSE](LICENSE) file for details.

```
Copyright (c) 2024 Roshan Shrestha

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.
```

---

## ⚠️ Disclaimer

**IMPORTANT: This tool is for EDUCATIONAL PURPOSES ONLY!**

### 🚨 Legal Notice

- **Educational Use Only**: This tool is designed for cybersecurity education and awareness training
- **No Malicious Intent**: Do not use for actual phishing attacks or malicious purposes
- **Responsible Usage**: Always obtain proper authorization before testing
- **Legal Compliance**: Ensure compliance with local laws and regulations

### 🛡️ Ethical Guidelines

1. **Authorization Required**: Only test on systems you own or have explicit permission to test
2. **Educational Context**: Use in controlled educational environments
3. **No Real Attacks**: Never use against real targets without permission
4. **Data Protection**: Handle captured data responsibly and securely

### 📚 Educational Purpose

This tool helps:
- **Security Awareness**: Understanding phishing techniques
- **Defense Training**: Learning to identify phishing attempts
- **Research**: Cybersecurity research and analysis
- **Testing**: Authorized security testing and assessment

---

## 👨‍💻 Author

**Roshan Shrestha**

- 🌐 **GitHub**: [@Roshanshrestha1](https://github.com/Roshanshrestha1)
- 📧 **Email**: [Your Email]
- 🔗 **LinkedIn**: [Your LinkedIn]
- 🐦 **Twitter**: [@YourTwitter]

---

## 🙏 Acknowledgments

- **Open Source Community**: For inspiration and contributions
- **Security Researchers**: For valuable insights and feedback
- **Beta Testers**: For testing and bug reports
- **Contributors**: Everyone who helped improve this project

---

## 📈 Project Statistics

<div align="center">

![GitHub stars](https://img.shields.io/github/stars/Roshanshrestha1/PhantomPhisherX?style=social)
![GitHub forks](https://img.shields.io/github/forks/Roshanshrestha1/PhantomPhisherX?style=social)
![GitHub issues](https://img.shields.io/github/issues/Roshanshrestha1/PhantomPhisherX)
![GitHub pull requests](https://img.shields.io/github/issues-pr/Roshanshrestha1/PhantomPhisherX)
![GitHub license](https://img.shields.io/github/license/Roshanshrestha1/PhantomPhisherX)

**⭐ Star this repository if you found it helpful!**

</div>

---

<div align="center">

**Made with ❤️ by Roshan Shrestha**

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Roshanshrestha1)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/yourprofile)
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/yourhandle)

</div>
