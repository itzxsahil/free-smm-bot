
<h1 align="center">🚀 FREE SMM BOT</h1>

<p align="center">
  <a href="https://github.com/your-username">
    <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=26&pause=1000&color=00BFFF&center=true&vCenter=true&width=800&lines=FREE+SMM+BOT;Instagram+%7C+YouTube+%7C+Telegram;Smart+Queue+%26+Auto+Order;Made+with+%E2%9D%A4%EF%B8%8F" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python" alt="Python">
  <img src="https://img.shields.io/badge/Telegram-Bot-blue?style=for-the-badge&logo=telegram" alt="Telegram">
  <img src="https://img.shields.io/badge/Selenium-Automation-green?style=for-the-badge" alt="Selenium">
  <img src="https://img.shields.io/badge/undetected--chromedriver-Stealth-orange?style=for-the-badge" alt="undetected-chromedriver">
</p>

---

## 🚀 Overview

A smart Telegram bot that automatically places free orders for:

- Instagram Likes, Views, Followers & Story Views  
- YouTube Likes  
- Telegram Views  

It uses a smart queue system, respects cooldowns, and automatically handles load.

---

## ✨ Features

- ✅ Smart Queue System
- ✅ Automatic Cooldown Management
- ✅ Exact Selectors (`#instagram-link` + `#submit-btn`)
- ✅ Admin-only commands
- ✅ Supports multiple services at the same time

---

## 📋 Available Services

| Command     | Service                  | Cooldown     |
|-------------|--------------------------|--------------|
| `ig_like`   | Instagram Likes          | 30 minutes   |
| `ig_view`   | Instagram Views          | 5 minutes    |
| `ig_follow` | Instagram Followers      | 24 hours     |
| `ig_story`  | Instagram Story Views    | 24 hours     |
| `yt_like`   | YouTube Likes            | 12 hours     |
| `tg_view`   | Telegram Views           | 3 hours      |

---

## 📦 Installation

```bash
pip install python-telegram-bot undetected-chromedriver selenium
```

Create a file named `config.json`:

```json
{
  "token": "YOUR_BOT_TOKEN",
  "admin_id": YOUR_TELEGRAM_ID
}
```

---

## ▶️ How to Run

```bash
python3 main.py
```

---

## 🤖 Commands

| Command                          | Description                     |
|----------------------------------|---------------------------------|
| `/order <service> <link> <qty>`  | Add order to queue              |
| `/que`                           | Show current queue              |
| `/services`                      | List all available services     |
| `/stop`                          | Stop the bot and clear queue     |

### Example:

```bash
/order ig_like https://www.instagram.com/p/xxxxx/ 5
/order ig_story https://www.instagram.com/stories/username/ 3
```

---

## ⚙️ How it Works

1. You add orders using `/order`
2. Bot places the order
3. Waits for the real service cooldown
4. Automatically starts the next available order

---

## 🛡 Notes

- Only the Admin (set in `config.json`) can use the bot
- Make sure your Chrome browser is up to date
- The bot uses `undetected-chromedriver` for better stability

---
# 🛡 License

Licensed under the **MIT License**.

---

# © Copyright

Copyright © 2026 **Sahil Tandon**

All rights reserved.

GitHub:
https://github.com/itz-dev-sahil

---

# ❤️ Respect Open Source

**Please don’t be a leech.**
If you copy someone’s work and present it as entirely your own without credit, you already know what that means.

Respect creators. 🤝

---

# 👨‍💻 Author

Made with ❤️ by **Sahil Tandon**

GitHub:
https://github.com/itz-dev-sahil

```
```
