# BotFeller Mod Desk

Live status page for u/BotFeller, the r/ClevelandGuardians moderation bot, for the sub's mod team.

The page is public, but the status data it shows is encrypted (AES-256-GCM, key from the team passcode via
PBKDF2-SHA256). A Mac updates `status.json` on the `data` branch every 2 minutes; the browser decrypts it
locally. Nothing readable is stored in this repository.
