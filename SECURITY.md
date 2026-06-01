# Security

## Downloads

Only trust beta builds from:

- https://github.com/MaxxWasHere/blossombeta/releases  
- The official Discord bot **`/downloadbeta`** link (beta role required)

Do not run copies from random Discord DMs or third-party upload sites.

## Antivirus / SmartScreen

Blossom is a PyInstaller-packaged Windows app. Some AV products flag new or unsigned executables heuristically. That is **not** proof of malware.

If you are unsure:

1. Download only from the URLs above.  
2. Upload the file to [VirusTotal](https://www.virustotal.com/) yourself.  
3. Run in a VM for initial testing if you prefer.

We do not ask for your Roblox password inside the macro. Webhook URLs are stored locally in your config.

## Beta license / activation

- Keys are issued per Discord user via the official bot.  
- Activation uses HTTPS to the Blossom license service.  
- A **hardware ID** hash binds each key to one machine.  
- Signed tokens are verified locally; private signing keys are **not** embedded in the client.

Reporting license abuse (key sharing, leaks): contact server admins.

## Reporting vulnerabilities

If you find a security issue in the **beta program** (activation bypass, key generation flaw, etc.):

1. Do **not** post public exploit steps in Discord.  
2. DM a server admin or project owner with reproduction details.  
3. Allow reasonable time to fix before public disclosure.

This repo does not contain source code; code-level issues in open components may be reported on the main Blossom project when applicable.
