# 24/7 AternosBot 4.2

<img alt="Discord" src="https://img.shields.io/discord/860809265689788447?label=discord&logo=Discord"> <img alt="GitHub all releases" src="https://img.shields.io/github/downloads/JodexIndustries/24-7-AternosBot/total?label=%D1%81%D0%BA%D0%B0%D1%87%D0%B8%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F">

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/H2H8GLWZE)
<div align="center">
    <a href="https://github.com/JodexIndustries/24-7-AternosBot/releases/latest"><img alt="Скачать" src="https://img.shields.io/badge/-СКАЧАТЬ_ПОСЛЕДНИЙ_РЕЛИЗ_(КЛИК)-blue?style=for-the-badge"/></a>
</div>


| <sub>EN</sub> [English](README.md) | <sub>RU</sub> [русский](README_RU.md) |
|------------------------------------|---------------------------------------|

Данный бот сделан для хостинга Aternos. Он не позволяет выключится серверу.

## OS

 * Windows 10/11
 * Linux
 * Mac

## Версия NodeJS

Версия: 14^

## Функции

 * Поддержка Minecraft 1.8, 1.9, 1.10, 1.11, 1.12, 1.13, 1.14, 1.15, 1.16, 1.17 и 1.18.
 * Анти афк
 * Управление через чат
 * [Настраиваемый конфиг](config.yaml)
 * [Настраиваемые файлы перевода](lang)
 * [Мультиаккаунт](accounts.txt) 
 * Авто респавн
 * Авто реконект

## Использование
Сначала установите nodejs >= 14 из [nodejs.org](https://nodejs.org/)

Для Linux:
Запустить install.sh , потом bot.sh

Для Windows
Запустить start.bat (установка пакетов и запуск bot.bat)

Если не работает через .sh .bat, написать в терминале:
```
npm install mineflayer fs util wait-until js-yaml
node .
```


### Управление через чат

 * ;start - включить анти афк
 * ;stop - выключить анти афк
 * ;pos - посмотреть координаты
