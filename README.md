# Twitch Extension Blocker

A uBlock Origin filter list that removes Twitch extensions completely, so they don't just sit there hidden.
This covers video overlays, the extension dock that appears when you hover the player, and extension panels under About.

- **Network:** blocks `ext-twitch.tv`, so extension code never loads.
- **Cosmetic:** hides the empty dock, the invisible overlay box and the leftover panel slots Twitch still draws.

Player controls, chat, Channel Points, Predictions/Polls and normal panels are not affected.

## Install

**One click:** [Subscribe in uBlock Origin](https://subscribe.adblockplus.org/?location=https%3A%2F%2Fraw.githubusercontent.com%2Fcharlescyso%2Ftwitch-extension-blocker%2Fmain%2Ftwitch-extensions.txt&title=Twitch%20Extension%20Blocker)

**Manually:** uBlock Origin → Dashboard → **Filter lists** → **Import** (at the bottom) → paste

```
https://raw.githubusercontent.com/charlescyso/twitch-extension-blocker/main/twitch-extensions.txt
```

→ **Apply changes**.

uBlock checks for updates every 4 days.

## Notes

- Tested 2026-10-18 on desktop Twitch, logged out and live.
- If Twitch renames its extension classes the dock may come back; open an issue.
