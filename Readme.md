<div align="center">

![Hermit Banner](https://i.ibb.co/sBWBFgD/a-professional-photograph-of-a-dark-hermit.jpg)

<br>

# 🧿 HERMIT 🧿

*The most powerful Python obfuscation engine*

<br>

[![Python](https://img.shields.io/badge/Python-3.12-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Cython](https://img.shields.io/badge/Cython-Powered-F7C948?style=for-the-badge&logo=cython&logoColor=black)](https://cython.org)
[![Termux](https://img.shields.io/badge/Termux-Only-1DBF73?style=for-the-badge&logo=android&logoColor=white)](#)
[![Subscription](https://img.shields.io/badge/Subscription-Required-FF4444?style=for-the-badge&logo=buymeacoffee&logoColor=white)](#contact)
[![MIT License](https://img.shields.io/badge/License-MIT-22C55E?style=for-the-badge&logo=opensourceinitiative&logoColor=white)](LICENSE)

</div>

---

## 📖 Overview

**Hermit** is the most powerful Python obfuscation engine, developed by **[Stein](https://t.me/rejerk)**

Hermit transforms Python source code into a highly secured, non-reversible format — making it virtually impossible to retrieve the original logic. Built on top of **Python** and **Cython**, it compiles scripts into native binaries with advanced encryption layers on top.

> 🔐 **Subscription Required** — Contact [@rejerk](https://t.me/rejerk) on Telegram to purchase access.

**Obfuscated output runs on:**

| Platform | Architecture |
|----------|-------------|
| 🖥️ Windows | x64 |
| 📱 Android | ARMv7 |
| 📱 Android | ARMv8 |

---

## 📦 Platform & Requirements

> [![Termux](https://img.shields.io/badge/Runs%20On-Termux-1DBF73?style=flat-square&logo=android&logoColor=white)](#)
> [![Python](https://img.shields.io/badge/Python-3.12%20Only-3776AB?style=flat-square&logo=python&logoColor=white)](#)

- Engine runs **only on Termux**
- Requires **Python 3.12** exclusively
- Obfuscated output runs on ARMv7, ARMv8, and Windows

---

## 🛠️ Installation

```bash
pkg update && pkg upgrade
pkg install git python -y
git clone https://github.com/devilstein1/hermit/
cd hermit
pip install -r requirements.txt
python enc.py req
```

---

## ⚙️ Usage

Hermit provides **3 modes** of operation:

---

### 1️⃣ Normal Mode

```bash
python enc.py
```

> Standard encryption flow — you select every option manually. Full control over which layers to apply and how.

📸 *Terminal Preview:*

![Normal Mode](https://github.com/devilstein1/hermit/blob/main/screenshots/Screenshot_20260309_155205_Termux.jpg)

---

### 2️⃣ Bot Mode

```bash
python enc.py bot
```

> Streamlined mode for **Telegram bots and automated scripts**. All encryption options are applied automatically — no manual configuration needed.

---

### 3️⃣ Site Mode ✨ `Recommended`

```bash
python enc.py site
```

> The **most powerful and convenient** way to encrypt. Hermit launches a local web server — interact with the full encryption UI from any browser on your WiFi/LAN network.

- 🌐 Access via local IP on any connected device
- 🖥️ Full web interface for all options
- ⚡ Fastest workflow for repeated use

🎬 *Live Interface:*

![Site Mode](https://github.com/devilstein1/hermit/blob/main/screenshots/Screen_Recording_20260309_154200_Chrome.gif)

---

## 🔐 Encryption Features

| Feature | Description |
|---------|-------------|
| ⚡ **Speed** | 2–3× faster than standard Python execution |
| 🛡️ **Irreversible** | Cannot be decoded back to original source |
| 🔒 **SteinCrypt** | Core obfuscation layer |
| 🔑 **STEINbest Strings** | String-level encryption |
| ✅ **Stability** | Almost zero runtime errors |

---

## ⚙️ Configuration

For complex scripts, encryption layers can be toggled in `settings.json`:

```json
{
  "steincrypt": true,
  "stein-best": true
}
```

> Set any option to `false` to disable that layer if compatibility issues arise.

---

## 📞 Contact

<div align="center">

[![Telegram](https://img.shields.io/badge/@rejerk-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/rejerk)
&nbsp;
[![Telegram Group](https://img.shields.io/badge/@keped%20%7C%20Group-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/keped)
&nbsp;
[![Instagram](https://img.shields.io/badge/@crying__kidz-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/crying_kidz)

</div>

---

## 📄 License

This project is licensed under the **MIT License** — free to use, modify, and distribute with proper credit to the original author.

---

## ⚠️ Disclaimer

This software is provided **strictly for educational purposes**. The author assumes **no responsibility** for misuse, malicious intent, or any consequences arising from the encrypted output.

---

<div align="center">

**STEIN · REJERK**

[![Telegram](https://img.shields.io/badge/Made%20by%20Stein-26A5E4?style=flat-square&logo=telegram&logoColor=white)](https://t.me/rejerk)

</div>
