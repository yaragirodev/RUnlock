<p align="center">
  <img src="readme-static/logo.png" width="80%"/>
</p>

<p align="center">
  <a href="https://github.com/AvenCores/Unlock_AI_and_EN_Services_for_Russia/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/AvenCores/Unlock_AI_and_EN_Services_for_Russia?style=flat-square" alt="License"/>
  </a>
  <a href="https://github.com/AvenCores/Unlock_AI_and_EN_Services_for_Russia/releases/latest">
    <img src="https://img.shields.io/github/v/release/AvenCores/Unlock_AI_and_EN_Services_for_Russia?style=flat-square" alt="Latest release"/>
  </a>
  <a href="https://github.com/AvenCores/Unlock_AI_and_EN_Services_for_Russia/releases">
    <img src="https://img.shields.io/github/downloads/AvenCores/Unlock_AI_and_EN_Services_for_Russia/total?style=flat-square" alt="Downloads"/>
  </a>
</p>

---

# Unlock AI & EN Services for Russia
**Magisk/KernelSU-модуль для обхода региональных блокировок зарубежных сервисов ИИ, социальных сетей, игр и других ресурсов из России.  
Дополнительно модуль блокирует вредоносные сайты.**

Форк - **yaragirodev**.  
Оригинальный проект — [AvenCores/Unlock_AI_and_EN_Services_for_Russia](https://github.com/AvenCores/Unlock_AI_and_EN_Services_for_Russia).

---

## Содержание
1. [Возможности](#возможности)  
2. [Требования](#требования)  
3. [Установка](#установка)  
4. [Обновление](#обновление)  
5. [Поддерживаемые сервисы](#поддерживаемые-сервисы)  
6. [ЧаВо](#чаво)  
7. [Журнал изменений](#журнал-изменений)  
8. [Лицензия](#лицензия)  
9. [Поддержка](#поддержка)

---

## Возможности
- Разблокировка более 70 популярных AI-, медиа- и облачных сервисов.  
- OTA-обновления через `update.json`.  
- Защита от скримеров и IP-логгеров.  
- Полностью офлайн-решение: без VPN, прокси и сторонних приложений.  

---

## Требования
- Android 8.0+  
- **Magisk** v23.0+ или **KernelSU** v0.8.0+  
- Отсутствие конфликтующих модулей, которые изменяют файл `hosts` (например, AdGuard-модули).  

---

## Установка
1. Скачайте последний релиз `Unlock_AI_and_EN_Services_for_Russia.VX.Y.Z.zip` из раздела [Releases](https://github.com/yaragirodev/RUnlock/releases/latest).  
2. В Magisk/KernelSU выберите «Установить из памяти» и укажите ZIP.  
3. Перезагрузите устройство.  

**Важно:** Если при установке появляется ошибка — сначала установите [v1.0.1](soon), затем обновитесь. Некоторые прошивки (особенно A-only) могут конфликтовать с новым форматом архива.  

---

## Обновление
- Проверка новой версии выполняется при каждом запуске Magisk/KernelSU-менеджера.  
- При наличии апдейта появится уведомление с предложением установить ZIP.  
- Журнал изменений подтягивается из [`changelog.md`](./changelog.md).  

---
## Поддерживаемые сервисы
Файл [`system/etc/hosts`](./source/system/etc/hosts) регулярно обновляется.  

| Категория              | Сервисы                                                                 |
|-------------------------|-------------------------------------------------------------------------|
| Социальные сети и мессенджеры | Instagram, TikTok, Truth Social, Guilded, 4PDA, Discord *(может быть нестабилен)* |
| ИИ-сервисы              | ChatGPT (включая Sora), Claude, Grok, Gemini, Google AI Studio / NotebookLM / Labs, Microsoft Copilot, GitHub Copilot, ElevenLabs, DeepL |
| Игры                    | Clash Royale, Clash of Clans, Brawl Stars, Xbox (включая Cloud Gaming), Microsoft Rewards |
| Музыка                  | Spotify, Tidal, Deezer                                                  |
| Почта и облако          | Proton Mail                                                            |
| Разработка              | GitHub (API & Copilot), JetBrains (Datalore, Plugins, CDN), Google AI API, NVIDIA Dev, Parsec, Manus API |
| Продуктивность          | Notion, Canva, Intel, Dell, Weather.com, Imgur, Web Archive, Tria.ge   |
| Здоровье                | Fitbit                                                                 |
| Платежи                 | Square / Squareup (через Tidal)                                        |
| Блокировка вредных сайтов | Скримеры: `only-fans.*`, `onlyfans.wtf` <br> IP-логгеры: `iplogger.org`, `grabify.org` и другие |


---

## ЧаВо
<details>
<summary>Почему некоторые сервисы недоступны?</summary>
Проблема может быть в DNS. Попробуйте Google (`8.8.8.8`) или Cloudflare (`1.1.1.1`). Можно использовать DoH/DoT.
</details>

<details>
<summary>Работает ли модуль в приложениях?</summary>
Гарантируется работа в веб-версии сервисов. В приложениях возможны дополнительные проверки региона.
</details>

<details>
<summary>Можно ли использовать с рекламными блокировщиками?</summary>
Да, но убедитесь, что AdGuard/другие адблокеры не перезаписывают `/system/etc/hosts`.
</details>

---

## Журнал изменений
См. [changelog.md](./changelog.md).  

---

## Лицензия
Распространяется по условиям [GPL-3.0 License](./LICENSE).  
Оригинал модуля сделан [AvenCores](https://github.com/AvenCores)

---

## Поддержка
Если хотите поддержать автора оригинального модуля:  
**SBER:** `2202 2050 7215 4401`
