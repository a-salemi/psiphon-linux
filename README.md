<h1 align="center">
  🚀 Psiphon Manager Bot & Auto Installer
</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Ubuntu%20%7C%20Debian-orange?style=for-the-badge&logo=linux" alt="Platform">
  <img src="https://img.shields.io/badge/Python-3.8+-blue?style=for-the-badge&logo=python" alt="Python">
  <img src="https://img.shields.io/badge/Bot-Telegram-blue?style=for-the-badge&logo=telegram" alt="Telegram">
  <img src="https://img.shields.io/badge/Developer-Amir%20Salemi-success?style=for-the-badge" alt="Developer">
</p>

<p align="center">
  <b>A powerful and smart script for the automated installation of Psiphon core, bundled with a Telegram management bot and a dedicated command-line tool.</b>
</p>

---

## 🌟 Features

- ⚙️ **Fully Automated Setup:** Install Psiphon core, configurations, and dependencies with a single line of code.
- 🤖 **Exclusive Telegram Bot:** Full server management (Start, Stop, Restart) directly from Telegram.
- 🌍 **Smart Location Changer:** Access over **30 different countries** using an interactive inline menu in Telegram.
- 💻 **Custom CLI Tool:** Quickly change server locations via terminal using the custom `changeloc` command.
- 🔄 **Auto Connection Check:** Smart system to verify and display the new IP address after changing locations.
- 🛡️ **High Security:** The Telegram bot responds exclusively to your configured `Admin ID`.

---

## 📋 Requirements

Before proceeding with the installation, ensure you have the following:
1. A Virtual Private Server (VPS) running **Ubuntu** or **Debian**.
2. Root (`root`) privileges.
3. A Telegram Bot Token (Get it from [@BotFather](https://t.me/BotFather)).
4. Your numeric Telegram User ID (Get it from [@userinfobot](https://t.me/userinfobot)).

---

## 🚀 Installation

To install the complete package (Psiphon + Telegram Bot + CLI Tool), simply copy and run the following command in your server's terminal:

```bash
bash <(curl -Ls (https://raw.githubusercontent.com/a-salemi/psiphon-linux/main/install.sh))
