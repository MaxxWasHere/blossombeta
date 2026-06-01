# Maintainer notes (releases only)

This repo is **binaries + docs**, not source.

## Publish a beta release

1. Build from the private/main Blossom tree:  
   `py scripts/build_all.py beta --beta-version 2.1.0-beta.1` (adjust flags as needed).
2. GitHub → **Releases** → **Draft a new release**.
3. Tag: `v2.1.0-beta.1` (match `APP_VERSION`).
4. Title: `Blossom 2.1.0-beta.1`
5. Paste the new section from [CHANGELOG.md](../CHANGELOG.md).
6. Upload `Blossom-2.1.0-beta.1.exe` — asset name must match bot `BETA_RELEASE_ASSET`.
7. Check **Pre-release**.
8. Publish.

## Bot link

Discord bot default:

`https://github.com/MaxxWasHere/blossombeta/releases/latest/download/Blossom-2.1.0-beta.1.exe`

Update `BETA_RELEASE_ASSET` / `DOWNLOAD_BETA_URL` on the laptop if the filename changes.

## Repo hygiene

- Do not commit `.exe` files (see `.gitignore`).
- Keep README version strings in sync with the latest tag when you ship.
