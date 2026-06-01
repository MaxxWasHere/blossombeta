# Getting started (beta)

## 1. Get access

You need a **beta tester** role in the official Discord server, then:

```
/getkey
```

Copy the key somewhere safe. It is tied to your Discord account and locks to the first PC you activate on.

## 2. Download & install

1. Open [Latest release](https://github.com/MaxxWasHere/blossombeta/releases/latest).
2. Download the `.exe` (e.g. `Blossom-2.1.0-beta.1.exe`).
3. Create a folder (e.g. `Blossom-Beta`) and put the exe inside.
4. Do **not** run from inside the ZIP without extracting.

Optional: use **`/downloadbeta`** in Discord for the same file (ephemeral link).

## 3. First launch

1. Run the exe. If Windows SmartScreen warns you, choose **More info → Run anyway** (only for files from this GitHub org).
2. Paste your license key when asked.
3. Walk through the intro: theme, webhooks, Roblox username, calibrations.
4. Set your **input delay** (ms) if clicks feel too fast.

## 4. Calibrations

Most features need one-time calibration (resolution-dependent):

- Merchant / shop regions  
- Potion slots and craft buttons  
- OCR failsafe (optional but recommended)

Video walkthrough: https://www.youtube.com/watch?v=s2S7Bncx9ns

Presets can be loaded from the Calibrations tab when available.

## 5. Webhooks (optional)

1. Create a Discord webhook in your server.
2. Paste the URL in Blossom settings.
3. Enable biome / merchant / status events as you like.
4. Use **Test webhook** to confirm.

## 6. Running a session

1. Open Roblox → Sol's RNG (private server link in settings if you use one).
2. Start the macro from the UI or hotkey.
3. Watch the status line / side panel for biome and module state.

Stop the macro before closing Roblox to avoid stuck inputs.

## 7. New PC?

```
/resethwid
```

Limited uses and cooldown apply. Admins can force-reset if you are locked out.

## 8. Updating

When a new beta tag is published on GitHub, download the new release asset. Your config in `%LOCALAPPDATA%\Blossom\` is kept. Re-activate only if prompted.

## Troubleshooting

| Problem | Try |
|---------|-----|
| Won’t start | Admin run, extract folder, valid key, not expired beta |
| Blank window | Install [WebView2](https://developer.microsoft.com/en-us/microsoft-edge/webview2/) |
| No merchant / no E press | Recalibrate merchant, check input delay |
| Wrong potions | Higher delay, recalibrate OCR failsafe |
| Key invalid | `/getkey` again if revoked; `/resethwid` if HWID mismatch |

See the main [README](../README.md) FAQ for more.
