# 24/7 AternosBot 4.1

[![Discord](https://img.shields.io/badge/chat-on%20discord-brightgreen.svg)](https://discord.gg/DP376QcGCJ)

| <sub>EN</sub> [English](README.md) | <sub>RU</sub> [русский](README_RU.md) |
|-------------------------|----------------------------|

This bot is made for Aternos hosting. It does not allow the server to shut down.

## OS

 * Windows 10/11
 * Linux
 * Mac

## NodeJS Version

Version: 14^

## Function

 * Support Minecraft 1.8, 1.9, 1.10, 1.11, 1.12, 1.13, 1.14, 1.15, 1.16, 1.17 and 1.18.
 * Anti Afk
 * Chat management 
 * [Custom config](config.json)
 * [Custom translation files](lang)
 * [Multi-Accounts](accounts.txt) 
 * Auto respawn
 * Auto reconnect

## Use
First install nodejs >= 14 of [nodejs.org](https://nodejs.org/)

For Linux:
Run install.sh , then bot.sh

For Windows
Run start.bat (install packages and run bot.bat)

If it does not work through .sh .bat, write in the terminal:
```
npm install mineflayer fs util wait-until
node .
```


### Chat management

 * ;start - enable anti afk
 * ;stop - turn off anti afk
 * ;pos - see coordinates
