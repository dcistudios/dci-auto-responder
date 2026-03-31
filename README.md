# <p align="center">🤖 DCI Auto Responder</p>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=38BDF8&center=true&vCenter=true&width=500&lines=DCI+Auto+Responder;Discord+Away+Message+Automation;Built+by+DCI+Studios;Fast+%7C+Reliable+%7C+Configurable" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Active-10B981?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Platform-Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" />
  <img src="https://img.shields.io/badge/Runtime-Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Organization-DCI_Studios-38BDF8?style=for-the-badge" />
</p>

-----

## 📖 Overview

**DCI Auto Responder** is a lightweight Discord selfbot away-message tool built and maintained by **DCI Studios**. Run it on your own account — when someone DMs you, it automatically replies with your custom away message, with a per-user cooldown so nobody gets spammed.

> ⚠️ This is a **selfbot** — it runs on your personal Discord account using your user token, not a bot token.  
> Use responsibly. Self-botting is against Discord’s ToS; you assume all risk.

-----

## ✨ Features

- 📨 Auto-replies to incoming DMs on your own account
- ✏️ Customizable away message via `message.txt`
- ⏱ Per-user cooldown to avoid spamming the same person
- 🔇 Ignores your own messages and non-DM channels
- 🪵 Console logging with timestamps for every auto-response
- ⚙️ Simple `.env` setup — no code changes needed

-----

## 🧰 Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=py,github" />
</p>

```
Python
discord.py-self
python-dotenv
```

-----

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/dcistudios/dci-auto-responder.git

# Navigate into the project
cd dci-auto-responder

# Install dependencies
pip install discord.py-self python-dotenv
```

-----

## ⚙️ Configuration

Rename `.env.example` to `.env` and fill in your values:

```env
DISCORD_TOKEN=your_user_token_here
COOLDOWN_MINUTES=30
```

|Variable          |Description                                  |Default |
|------------------|---------------------------------------------|--------|
|`DISCORD_TOKEN`   |Your Discord **user token**                  |Required|
|`COOLDOWN_MINUTES`|Minutes before re-responding to the same user|`30`    |


> ⚠️ Never share or commit your `.env` file — it’s already in `.gitignore`.  
> Your user token gives full access to your account. Keep it private.

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

The selfbot will log in as you and begin watching for DMs. Each auto-response is logged to the console with a timestamp.

```
Logged in as YourName#0000
Auto-responder active.
[14:23:01] Auto-responded to SomeUser
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
