# Telegram Auto-Chat & Catch Bot

A high-performance, multi-account Telegram automation tool built with **Python** and **Telethon**. This bot is designed to handle automated conversations, forward specific game events, and execute "catch" commands for Waifu-style bots with human-like delays.

## ✨ Key Features

- **Multi-Session Management:** Run and sync multiple Telegram accounts simultaneously.
- **Auto-Catch Logic:** Automatically detects character spawns and sends `/catch` commands.
- **Intelligent Forwarding:** Forwards specific spawn messages to designated channels/users.
- **Human-Like Chatting:** Includes a "Natural Chat Loop" with randomized scenarios (Gaming, Food, Movies, Daily Life) to maintain account health and avoid spam flags.
- **Smart Throttling:** Built-in handling for `FloodWaitError` and randomized delays ($6.5s - 9.0s$) to mimic human behavior.
- **UTF-8 Console Support:** Full support for Persian/Emoji rendering in the terminal.

## 🛠 Prerequisites

Ensure you have Python 3.8+ installed. You will also need to install the following dependencies:

```bash
pip install telethon colorama
