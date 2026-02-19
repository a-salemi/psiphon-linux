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

## 🎯 Why Use This? (Use Cases)

If you have a VPN server (like X-UI, Marzban, etc.), you might face issues like **IP bans**, **blocked websites (OpenAI, Netflix, Spotify)**, or **strict datacenter firewalls**. 

This script installs **Psiphon** in the background of your server and gives you a clean, dynamic local proxy. You can use this proxy to:
* **Bypass Geo-blocks:** Change your server's outgoing IP to 30+ different countries instantly.
* **Smart Routing:** Route only specific blocked websites (like ChatGPT or Binance) through Psiphon while keeping normal traffic on your main high-speed IP.
* **Hide VPS IP:** Prevent your main server IP from being exposed or blocked by destination websites.

---

## 🌟 Features

- ⚙️ **Fully Automated Setup:** Install Psiphon core, configurations, and dependencies with a single line of code.
- 🤖 **Exclusive Telegram Bot:** Full server management (Start, Stop, Restart, Change Location) directly from Telegram.
- 🌍 **Smart Location Changer:** Access over **30 different countries** using an interactive inline menu in Telegram.
- 💻 **Custom CLI Tool:** Quickly change server locations via terminal using the custom `changeloc` command.
- 🔄 **Auto Connection Check:** Smart system to verify and display the new IP address after changing locations.

---

## 📋 Requirements

1. A Virtual Private Server (VPS) running **Ubuntu** or **Debian**.
2. Root (`root`) privileges.
3. A Telegram Bot Token (Get it from [@BotFather](https://t.me/BotFather)).
4. Your numeric Telegram User ID (Get it from [@userinfobot](https://t.me/userinfobot)).

---

## 🚀 Installation

To install the complete package, simply copy and run the following command in your server's terminal:

```bash
bash <(curl -Ls https://raw.githubusercontent.com/a-salemi/psiphon-linux/main/install.sh)

