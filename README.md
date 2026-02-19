<h1 align="center">
  🚀 Psiphon Manager Bot & Auto Installer
</h1>

<p align="center">
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
* **Smart Routing:** Route only specific blocked websites through Psiphon while keeping normal traffic on your main high-speed IP.
* **Hide VPS IP:** Prevent your main server IP from being exposed or blocked.

---

## 🌟 Features

- ⚙️ **Fully Automated Setup:** Install Psiphon core, configurations, and dependencies with a single line of code.
- 🤖 **Exclusive Telegram Bot:** Full server management (Start, Stop, Restart, Change Location) directly from Telegram.
- 🌍 **Smart Location Changer:** Access over **30 different countries** using an interactive inline menu in Telegram.
- 💻 **Custom CLI Tool:** Quickly change server locations via terminal using the custom `changeloc` command.
- 🔄 **Auto Connection Check:** Smart system to verify and display the new IP address.

---

## 📋 Requirements

1. A Virtual Private Server (VPS) running **Ubuntu** or **Debian**.
2. Root (`root`) privileges.
3. A Telegram Bot Token (Get it from @BotFather).
4. Your numeric Telegram User ID (Get it from @userinfobot).

---

## 🚀 Installation

To install the complete package, simply copy and run the following command in your server's terminal:

<pre><code>bash <(curl -Ls https://raw.githubusercontent.com/a-salemi/psiphon-linux/main/install.sh)
</code></pre>


During the installation, the script will prompt you for your **Token** and **Admin ID**. Enter them and wait for the magic to happen! 🎉

---

## 🔗 How to Connect (Integration with X-UI / Marzban)

Once installed, Psiphon runs quietly in the background and creates a **Local SOCKS5 Proxy**. 

You can easily route your panel's traffic through it. Here is how to configure it as an Outbound in **X-UI (Sanaei)**:

1. Go to the **Outbounds** section in your X-UI panel.
2. Click on **Add Outbound**.
3. Fill in the following details:
   * **Tag:** `psiphon-out`
   * **Protocol:** `socks`
   * **Address:** `127.0.0.1`
   * **Port:** `2080`
4. Now, go to the **Routing Rules** section.
5. Create a new rule, select the domains you want to bypass (e.g., `geosite:openai`), and set their outbound tag to `psiphon-out`.

---

## 📱 Telegram Bot & CLI Usage

### Telegram Bot
Go to your Telegram bot and send `/start`. You will see buttons to:
* 📊 Check Service Status & Current IP.
* 🌍 Open an inline menu to switch between 30+ countries instantly.
* ▶️ Start / ⏹ Stop / 🔄 Restart the service.

### CLI Tool
If you are in the terminal (SSH) and want to change the location, just type:
<pre><code>changeloc</code></pre>
Enter the two-letter country code, and the tool will do the rest!

---

## 👨‍💻 Developer

Developed with ❤️ by **Amir Salemi**.
If you found this project helpful, please consider giving it a star (⭐)!

---

## 📜 License
This project is open-source and available under the MIT License.

If you have a VPN server (like X-UI, Marzban, etc.), you might face issues like **IP bans**, **blocked websites (OpenAI, Netflix, Spotify)**, or **strict datacenter firewalls**. 

This script installs **Psiphon** in the background of your server and gives you a clean, dynamic local proxy. You can use this proxy to:
* **Bypass Geo-blocks:** Change your server's outgoing IP to 30+ different countries instantly.
* **Smart Routing:** Route only specific blocked websites through Psiphon while keeping normal traffic on your main high-speed IP.
* **Hide VPS IP:** Prevent your main server IP from being exposed or blocked.

---

## 🌟 Features

- ⚙️ **Fully Automated Setup:** Install Psiphon core, configurations, and dependencies with a single line of code.
- 🤖 **Exclusive Telegram Bot:** Full server management (Start, Stop, Restart, Change Location) directly from Telegram.
- 🌍 **Smart Location Changer:** Access over **30 different countries** using an interactive inline menu in Telegram.
- 💻 **Custom CLI Tool:** Quickly change server locations via terminal using the custom `changeloc` command.
- 🔄 **Auto Connection Check:** Smart system to verify and display the new IP address.

---

## 📋 Requirements

1. A Virtual Private Server (VPS) running **Ubuntu** or **Debian**.
2. Root (`root`) privileges.
3. A Telegram Bot Token (Get it from @BotFather).
4. Your numeric Telegram User ID (Get it from @userinfobot).

---

## 🚀 Installation

To install the complete package, simply copy and run the following command in your server's terminal:

<pre><code>bash <(curl -Ls (https://raw.githubusercontent.com/a-salemi/psiphon-linux/main/install.sh))</code></pre>


During the installation, the script will prompt you for your **Token** and **Admin ID**. Enter them and wait for the magic to happen! 🎉

---

## 🔗 How to Connect (Integration with X-UI / Marzban)

Once installed, Psiphon runs quietly in the background and creates a **Local SOCKS5 Proxy**. 

You can easily route your panel's traffic through it. Here is how to configure it as an Outbound in **X-UI (Sanaei)**:

1. Go to the **Outbounds** section in your X-UI panel.
2. Click on **Add Outbound**.
3. Fill in the following details:
   * **Tag:** `psiphon-out`
   * **Protocol:** `socks`
   * **Address:** `127.0.0.1`
   * **Port:** `2080`
4. Now, go to the **Routing Rules** section.
5. Create a new rule, select the domains you want to bypass (e.g., `geosite:openai`), and set their outbound tag to `psiphon-out`.

---

## 📱 Telegram Bot & CLI Usage

### Telegram Bot
Go to your Telegram bot and send `/start`. You will see buttons to:
* 📊 Check Service Status & Current IP.
* 🌍 Open an inline menu to switch between 30+ countries instantly.
* ▶️ Start / ⏹ Stop / 🔄 Restart the service.

### CLI Tool
If you are in the terminal (SSH) and want to change the location, just type:
<pre><code>changeloc</code></pre>
Enter the two-letter country code, and the tool will do the rest!

---

## 👨‍💻 Developer

Developed with ❤️ by **Amir Salemi**.
If you found this project helpful, please consider giving it a star (⭐)!

---

## 📜 License
This project is open-source and available under the MIT License.
