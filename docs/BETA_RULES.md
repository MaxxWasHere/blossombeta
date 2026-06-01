# Beta tester rules

Short version of what we expect while you use Blossom beta builds.

## Do

- Use **your own** `/getkey` license on **your own** PC.
- Report bugs, crashes, and false detections in Discord with version number (shown in the app).
- Keep downloads from **GitHub Releases** or **`/downloadbeta`** only.
- Move PC with `/resethwid` when you genuinely change hardware.

## Don’t

- Share your license key, the beta exe, or download links with non-testers.
- Upload the beta to file hosts, Discord DMs (public), or YouTube “free download” posts.
- Run multiple accounts on one key to bypass HWID (will be revoked).
- Expect stable-release polish — beta can break between releases.

## What happens if rules are broken

- Key **revoked** (`/blossomadmin revoke`) — macro stops activating.
- Beta role removed — no new keys or `/downloadbeta`.
- Build may **expire** on a schedule for old betas.

## Privacy

Activation sends a **hardware fingerprint** (machine ID–style hash, not your name or files) to the license server so keys cannot be duplicated. See [SECURITY.md](../SECURITY.md).
