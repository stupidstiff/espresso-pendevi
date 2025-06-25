<img src="https://cdn-icons-png.flaticon.com/512/7618/7618040.png" class="logo" width="120"/>

# ESPRESSO-PENDEVI

```markdown
# ☕ espresso-pendevi
```
> ⚠️ **WORK IN PROGRESS** - This project is currently under active development and not ready for production use.






**A powerful pentesting device based on ESP32-C6 with touchscreen GUI and WebUI interface.**

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Status](https://img.shields.io/badge/status-WIP-orange.svg)
![Platform](https://img.shields.io/badge/platform-ESP32--C6-green.svg)

</div>

---

## 🚨 **LEGAL DISCLAIMER & EDUCATIONAL PURPOSE ONLY**

**⚖️ IMPORTANT LEGAL NOTICE:**

This project is **STRICTLY FOR EDUCATIONAL AND AUTHORIZED TESTING PURPOSES ONLY**.

- ✅ **ONLY USE ON YOUR OWN NETWORKS** or with explicit written permission
- ✅ **WHITE HAT / ETHICAL HACKING ONLY** - Authorized penetration testing
- ✅ **EDUCATIONAL RESEARCH** - Learning cybersecurity concepts
- ❌ **NO UNAUTHORIZED ACCESS** - Illegal in most jurisdictions
- ❌ **NO MALICIOUS USE** - Not for attacking others' networks
- ❌ **NO COMMERCIAL EXPLOITATION** without proper licensing

**By using this software, you agree to:**
- Comply with all applicable local, state, and federal laws
- Only test networks you own or have explicit written authorization to test
- Use this tool responsibly and ethically
- Not hold the author liable for any misuse or legal consequences

**The author disclaims all responsibility for illegal or unethical use of this software.**

---

## 📱 Hardware Specifications

<div align="center">

| Component | Specification |
|-----------|---------------|
| **Microcontroller** | Waveshare ESP32-C6-PICO-Touch-LCD-1.47 |
| **Display** | 1.47" capacitive touchscreen (172x320) |
| **Driver** | GC9A01 display + CST816T touch |
| **Connectivity** | WiFi 6, Bluetooth 5.3, Zigbee, Thread |
| **Storage** | MicroSD card slot |
| **Interface** | USB-C, GPIO pins, buzzer |

</div>

---

## ✨ Features Overview

### 🔍 **WiFi Analysis Suite**
- 📡 Network scanner with detailed information
- 🎯 Access point enumeration and monitoring  
- 👥 Client device detection and tracking
- 📊 Signal strength analysis and visualization
- 📻 Channel utilization monitoring

### 🛡️ **Penetration Testing Tools**
- ⚡ Deauthentication attack capabilities
- 📢 Beacon frame injection and spamming
- 🎭 Evil twin / Rogue access point creation
- 🔑 PMKID capture for offline analysis
- 📦 Packet sniffing and real-time analysis
- 🤝 WiFi handshake capture and storage

### 📱 **Bluetooth Analysis**
- 🔵 Bluetooth Classic device enumeration
- 🔷 BLE (Bluetooth Low Energy) scanning
- 🔍 Device fingerprinting and identification
- 📋 Service and characteristic enumeration

### 🌐 **Web Interface**
- 🖥️ Remote control via responsive WebUI
- ⚡ Real-time monitoring and status updates
- ⚙️ Configuration management interface
- 📄 Log file access and download
- 📱 Mobile-friendly responsive design

### 📱 **Touchscreen GUI**
- 🎨 Intuitive touch-based navigation
- 📊 Real-time status and data visualization
- 🎯 Context-aware menu system
- 🎨 Customizable themes and layouts

---

## 🚀 Quick Start Guide

### 📋 **Prerequisites**

- **Development Environment:** macOS/Linux/Windows
- **Framework:** ESP-IDF v5.x or PlatformIO  
- **IDE:** Visual Studio Code (recommended)
- **Python:** 3.8+ with virtual environment support

### 🛠️ **Installation Steps**

1. **📥 Clone Repository**
```

git clone https://github.com/stiff/espresso-pendevi.git
cd espresso-pendevi

```

2. **🐍 Setup Python Environment**
```


# Create and activate virtual environment

python3 -m venv ~/espresso-pendevi-env
source ~/espresso-pendevi-env/bin/activate

# Install required packages

pip install -r requirements.txt

```

3. **⚙️ Configure ESP-IDF**
```


# Set target platform

idf.py set-target esp32c6

# Open configuration menu

idf.py menuconfig

```

4. **🔨 Build & Flash**
```


# Compile firmware

idf.py build

# Flash to device (replace with your port)

idf.py -p /dev/ttyUSB0 flash monitor

```

---

## 🤝 Contributing

Contributions are welcome! Please ensure all contributions maintain the educational and ethical focus of this project.

### 📝 **Contribution Guidelines**
- Fork the repository and create a feature branch
- Ensure code follows project standards and documentation
- Add appropriate tests for new functionality
- Submit pull request with detailed description
- All contributions must comply with educational use disclaimer

---

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for complete details.

---

## 🔒 Security & Responsible Disclosure

If you discover security vulnerabilities in this educational project, please report them responsibly through our [Security Policy](SECURITY.md).

---

## 📞 Support & Community

- **🐛 Issues:** [GitHub Issues](https://github.com/stiff/espresso-pendevi/issues)
- **💬 Discussions:** [GitHub Discussions](https://github.com/stiff/espresso-pendevi/discussions)  
- **📚 Documentation:** [Project Wiki](https://github.com/stiff/espresso-pendevi/wiki)

---

<div align="center">

**  Made with ☕️ by stiff**

*Remember: With great power comes great responsibility. Use wisely! 🕷️*

</div>
```

