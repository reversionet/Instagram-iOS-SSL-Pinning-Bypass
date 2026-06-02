# <img src="https://img.icons8.com/fluency/48/instagram-new.png" width="28"/> Instagram iOS SSL Pinning Bypass

> A patched version of Instagram for iOS with SSL/TLS certificate pinning disabled — enabling HTTPS traffic inspection for security research, reverse engineering, and mobile application analysis.

![Platform](https://img.shields.io/badge/Platform-iOS-black?style=flat-square&logo=apple)
![Version](https://img.shields.io/badge/Latest%20Patch-395.0.0-blue?style=flat-square)
![Jailbreak](https://img.shields.io/badge/Jailbreak-Not%20Required-green?style=flat-square)
![Frida](https://img.shields.io/badge/Frida-Not%20Required-green?style=flat-square)
![License](https://img.shields.io/badge/Use-Educational%20Only-orange?style=flat-square)
![Tested On](https://img.shields.io/badge/Tested%20on-iOS%2015.4.1-informational?style=flat-square)

---

## ✨ Features

| Feature | Status |
|---|---|
| 🔓 No jailbreak required | ✅ |
| 🧪 No Frida required | ✅ |
| 🔒 SSL/TLS certificate pinning removed | ✅ |
| 🌐 HTTPS traffic interception via proxy | ✅ |
| 📱 iOS compatible | ✅ |

---

## 📖 About SSL Pinning

SSL pinning (also known as certificate pinning) is a security mechanism that prevents applications from trusting certificates outside a predefined set. This repository demonstrates how SSL pinning can be removed through binary patching for **research and educational purposes**.

🔗 [Read more: How to Bypass Certificate Pinning on Instagram](https://yinsolutions.org/blogs/how-to-bypass-certificate-pinning-ig.html)

---

## ℹ️ Info

| Field | Details |
|---|---|
| 📦 Latest patched version | `395.0.0` |
| 📱 Platform | iOS |
| 🧪 Tested on | iOS 15.4.1 |
| 🔍 Traffic inspection | Via supported HTTPS proxy |

---

## 📥 Installation

1. **Download** the IPA file from the table below.
2. **Install** using one of:
   - [Sideloadly](https://sideloadly.io/)
   - [TrollStore](https://github.com/opa334/TrollStore) *(recommended)*
3. **Configure** your HTTPS interception proxy before launching.
4. **Launch** Instagram and begin inspecting traffic.

### 🌐 Supported Proxies

| Proxy | Status |
|---|---|
| [mitmproxy](https://mitmproxy.org/) | ✅ Tested |
| [Burp Suite](https://portswigger.net/burp) | ✅ Supported |
| [Charles Proxy](https://www.charlesproxy.com/) | ✅ Supported |
| [Proxyman](https://proxyman.io/) | ✅ Supported |

---

## 📦 Available Release

| App | Bundle ID | Version | Type | SSL Bypass | Download |
|---|---|---|---|---|---|
| <img src="https://img.icons8.com/fluency/20/instagram-new.png"/> Instagram | `com.burbn.instagram` | `395.0.0` | IPA | 🟢 Bypassed | [⬇️ Download](https://github.com/reversionet/Instagram-iOS-SSL-Pinning-Bypass/releases/download/v395/Instagram395.ipa) |

---

## ⚠️ Known Issues

### 💥 Application Crashes After Login

Some users have reported crashes after signing in when using certain sideloading methods.

> **✅ Recommended fix:** Install the IPA using **TrollStore**. This has proven to be the most reliable method for avoiding post-login crashes.

---

## 🗂️ Other Apps

Additional bypassed applications may be available. Check [my repositories](https://github.com/reversionet) for current releases and updates.

---

## 🎓 SSL Pinning & Jailbreak Detection Training

Interested in learning how SSL pinning bypasses, jailbreak detection bypasses, and mobile application patching work?

Training, private courses, and custom app requests are available.

📲 **Telegram:** [@reversio1](https://t.me/reversio1)

---

## ⚖️ Disclaimer

> This project is provided **strictly for educational, research, and testing purposes**.
>
> The purpose of this repository is to help security researchers, developers, and reverse engineers better understand SSL/TLS certificate pinning and mobile application security mechanisms.
>
> Users are solely responsible for ensuring their activities comply with applicable laws, regulations, and terms of service. The author assumes **no responsibility** for misuse, damages, or legal consequences resulting from the use of this project.

📧 Concerns? Contact: [disclaimer@reversio.net](mailto:disclaimer@reversio.net)
