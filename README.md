# BDGhost - Stealth VPN Android App 🇧🇩👻

BDGhost is a custom stealth VPN Android application built using Kotlin and Android Studio.  
It supports **Host** and **Client** modes in a single app and is optimized for use with apps like **bKash**, **Nagad**, and other BD-only services — even when you're outside Bangladesh.

---

## ✨ Features

- 🔀 Dual Mode: Host & Client in one APK
- 🔒 Built-in WireGuard + ZeroTier support
- 🌐 Manual ZeroTier Address input
- 📍 Mock location support (Dhaka)
- 🌓 Dark themed premium UI
- 🧠 DNS Selector (BDIX, Google, Cloudflare, Custom)
- 🚀 Auto-connect on launch
- 🛡️ Anti-DNS Leak and stealth firewall mode

---

## 📦 How to Build (Android Studio or AndroidIDE)

### 🖥️ Android Studio

```bash
git clone https://github.com/yourusername/BDGhost.git
cd BDGhost
./gradlew assembleDebug