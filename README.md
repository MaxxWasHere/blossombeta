# Blossom Beta

Pre-release builds of **[Blossom](https://github.com/MaxxWasHere/Blossom)** — a free macro for **Sol's RNG** (biomes, auras, merchant, potions, Discord webhooks, and more).

This repository ships **compiled releases only**. Source code is not published here. Stable builds live on the main [Blossom](https://github.com/MaxxWasHere/Blossom) repo.

---

## Download

| Build | Where |
|-------|--------|
| **Beta** (this repo) | [**Latest beta release**](https://github.com/MaxxWasHere/blossombeta/releases/latest) → download `Blossom-2.1.0-beta.1.exe` (name may change per version) |
| **Stable** | [**Blossom releases**](https://github.com/MaxxWasHere/Blossom/releases/latest) → `BlossomMacro.exe` |

In Discord, beta testers can also use **`/downloadbeta`** (beta role required) for a direct download link.

---

## Beta access (required)

Beta builds **will not run** without activation:

1. Join the Blossom Discord server (link in server announcements).
2. Get the **beta tester** role.
3. Run **`/getkey`** in Discord — you receive a **personal license key** (one per account).
4. Install the beta from [Releases](https://github.com/MaxxWasHere/blossombeta/releases/latest), extract to a folder, and run it.
5. Enter your key when prompted. The key binds to **your PC** (hardware ID).

- **`/resethwid`** — move your key to a new PC (limited uses; cooldown applies).
- Lost access or leaked key? Contact an admin — keys can be revoked.

Do **not** share your key or the beta file with non-testers. Redistribution breaks the beta program.

---

## Requirements

- **Windows 10/11**
- **Roblox** + Sol's RNG
- **[WebView2 Runtime](https://developer.microsoft.com/en-us/microsoft-edge/webview2/)** (if the window is blank/black)
- Discord (for keys and optional webhooks)

---

## Quick start

1. Download the `.exe` from [Releases](https://github.com/MaxxWasHere/blossombeta/releases/latest).
2. Put it in its **own folder** (config is saved next to the app / in `%LOCALAPPDATA%\Blossom\`).
3. Run as **Administrator** if the macro does not start.
4. Complete the in-app setup (theme, webhooks, calibrations).
5. Activate with your **`/getkey`** license key.

Tutorial (calibrations): [YouTube guide](https://www.youtube.com/watch?v=s2S7Bncx9ns)

More detail: [docs/GETTING_STARTED.md](docs/GETTING_STARTED.md)

---

## What's in the beta?

See [CHANGELOG.md](CHANGELOG.md) for version history.

Highlights for **2.1.x beta** (on top of Blossom 2.0):

- Online license activation (Discord-issued keys, HWID-bound)
- Reworked automations (merchant, quests, scheduling)
- Revamped UI, intro flow, floating side panels
- Improved Discord webhooks (biomes, currency, merchant)

---

## FAQ

**Is it a virus?**  
Windows may flag packed executables. This is a common false positive. Only download from this repo’s **Releases** or the official Discord bot link. Scan on [VirusTotal](https://www.virustotal.com/) if you want extra assurance.

**Macro won’t start?**  
Extract to a folder, run as admin, install WebView2, and make sure you activated with a valid beta key.

**Screen is black or white?**  
Install [WebView2](https://developer.microsoft.com/en-us/microsoft-edge/webview2/).

**Wrong potions / misclicks?**  
Increase input delay (1000–2000 ms) or recalibrate OCR failsafe (Arial/Rubik font works well).

**Stable vs beta?**  
Stable is for everyday use. Beta has newer features and may break — report bugs in Discord.

---

## Support & feedback

- Bugs and feedback: Discord support channel (same server as `/getkey`).
- Security concerns: [SECURITY.md](SECURITY.md)

---

## License

Blossom is based on the [Noteab / Coteab macro](https://github.com/xVapure/Noteab-Macro) lineage and distributed under the **Apache License 2.0**. See [LICENSE](LICENSE) and [NOTICE](NOTICE).

Beta binaries are provided as-is for authorized testers only.
