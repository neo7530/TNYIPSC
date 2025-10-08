# TNYIPSC (coming soon)

## MOTOTRBO ⇄ HBLink Gateway

**TNYIPSC** is a lightweight gateway software that connects a Motorola DMR repeater (e.g., MOTOTRBO DR-3000) directly to a FreeDMR-compatible DMR server (HBLink, MMDVM protocol).

### ✅ Features

- Bidirectional support for:
  - Voice
  - Data
  - SDS (Short Data Service)
  - Talker Alias
  - D-APRS (Digital APRS)
- Compatible with:
  - MOTOTRBO repeaters
  - FreeDMR networks
  - HBLink servers
  - MMDVM protocol

---

## 🚀 Getting Started

1. **Download** TNYIPSC for your preferred platform.
2. **Edit** the configuration file to match your repeater and network settings.
3. **Run** the software.

---

## 🔓 Licensing Modes

### Unlicensed Mode
- Allows connection from repeater to HBLink network.
- You can **listen** to any conversation.
- **Limitations**:
  - Reverse transmission (IPSC → HBLink) is disabled.
  - Daemon mode is not supported.
  - Program exits automatically after 15 minutes.

### Licensed Mode
- Enables full bidirectional communication.
- Supports daemon mode and long-term operation.
- Requires a valid license key.

---

## 📁 Configuration

Edit the configuration file (`tnyipsc.conf`) to set:

- Repeater IP and port
- HBLink server address port and password
- Talkgroup mappings via Option-Line
- etc...

---

## 📜 License

TNYIPSC is proprietary software.  
Unlicensed use is permitted for testing and monitoring purposes only.  
For full functionality, a license key must be obtained from the developer.

---

## 🛠️ Support

For documentation, updates, and licensing inquiries, visit:  
this github repository.

---

