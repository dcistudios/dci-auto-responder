# <p align="center">🤖 DCI Auto Responder</p>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=38BDF8&center=true&vCenter=true&width=500&lines=DCI+Auto+Responder;Intelligent+Discord+Automation;Built+by+DCI+Studios;Fast+%7C+Reliable+%7C+Configurable" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Active-10B981?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Platform-Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" />
  <img src="https://img.shields.io/badge/Runtime-Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Organization-DCI_Studios-38BDF8?style=for-the-badge" />
</p>

-----

## 📖 Overview

**DCI Auto Responder** is a lightweight Discord DM automation tool built and maintained by **DCI Studios**. When someone slides into your DMs, it automatically replies with a custom away message — with a configurable cooldown so users don’t get spammed.

> 🔒 This project is part of DCI Studios’ private-first development model and is released as an official public tool.

-----

## ✨ Features

- 📨 Responds automatically to incoming Discord DMs
- ✏️ Fully customizable message via `message.txt`
- ⏱ Per-user cooldown to prevent repeat responses
- 🔇 Ignores messages from itself and non-DM channels
- 🪵 Console logging with timestamps for every auto-response
- ⚙️ Simple `.env` configuration — no code changes needed

-----

## 🧰 Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=py,github" />
</p>

```
Python
discord.py
python-dotenv
```

-----

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/gangbusinessinquires-rgb/dci-auto-responder.git

# Navigate into the project
cd dci-auto-responder

# Install dependencies
pip install discord.py python-dotenv
```

-----

## ⚙️ Configuration

Create a `.env` file in the root directory:

```env
DISCORD_TOKEN=your_bot_token_here
COOLDOWN_MINUTES=30
```

|Variable          |Description                                  |Default |
|------------------|---------------------------------------------|--------|
|`DISCORD_TOKEN`   |Your Discord bot token                       |Required|
|`COOLDOWN_MINUTES`|Minutes before re-responding to the same user|`30`    |


> ⚠️ Never share or commit your `.env` file. Add it to `.gitignore`.

-----

## ✏️ Custom Message

Edit `message.txt` to set your away message:

```
Hey! I'm not around right now, I'll get back to you soon.
```

If `message.txt` is not found, the bot falls back to the default message above.

-----

## 🚀 Usage

```bash
python main.py
```

The bot will log in and begin watching for DMs automatically. Each auto-response is logged to the console with a timestamp and the recipient’s username.

```
Logged in as YourBot#0000
Auto-responder active.
[14:23:01] Auto-responded to SomeUser#1234
```

-----

## 🌐 Official Links

<p align="center">
  <a href="https://dcistudios.xyz">
    <img src="https://img.shields.io/badge/DCI_Studios-Website-38BDF8?style=for-the-badge" />
  </a>
  <a href="https://hosting.dcistudios.xyz">
    <img src="https://img.shields.io/badge/DCI_Hosting-Infrastructure-0EA5E9?style=for-the-badge" />
  </a>
  <a href="https://forums.dcistudios.xyz">
    <img src="https://img.shields.io/badge/DCI_Forums-Community-8B5CF6?style=for-the-badge" />
  </a>
  <a href="https://thecarter.xyz">
    <img src="https://img.shields.io/badge/Carter-Portfolio-6366F1?style=for-the-badge" />
  </a>
</p>

-----

## 👑 Leadership

**Owner & Founder:** Carter  
**Organization:** DCI Studios

-----

## 📬 Contact

<p align="center">
  <a href="mailto:developer@dcistudios.xyz">
    <img src="https://img.shields.io/badge/Email-developer@dcistudios.xyz-D14836?style=flat-square&logo=gmail&logoColor=white" />
  </a>
</p>

-----

<p align="center">
<b>DCI Studios — Architecting Excellence.</b>
</p>
