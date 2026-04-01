# 🛠️ Raspberry Pi 5 Build Log: The "Ad-Slayer"

This project documents the physical assembly and software configuration of my Raspberry Pi 5. This board will eventually serve as a network-wide ad-blocker (Pi-hole) and recursive DNS server.

## 📦 The Kit & Components
I started with a CanaKit bundle to ensure I had a reliable power supply and the official case options.

![CanaKit Bundle Contents](Canakit%20RPi5.jpg)

## 🔍 Unboxing & Preparation
Safety first—I used an ESD mat and wrist strap during the unboxing. I also have my personal USB-C card reader ready for flashing the OS once I resolve the display situation.

![Unboxed Components](Pi%205%20Unboxed.jpg)

## ✅ Final Assembly
The active cooler is installed and the board is seated. Even without a monitor, the hardware is ready for its first boot.

![Assembled Raspberry Pi 5](Raspberry%20Pi%205.jpg)

---
## 🚧 Current Status: Headless Setup
Because the monitors in the hut are VGA-only, I am currently looking into:
1. **Headless SSH:** Enabling SSH via the Raspberry Pi Imager to configure the Pi without a monitor.
2. **Adapters:** Sourcing a Micro-HDMI to VGA active adapter.

### Next Steps
- [x] Hardware Assembly
- [ ] Flash Raspberry Pi OS Lite
- [ ] Initial SSH Connection
- [ ] Pi-hole Installation
