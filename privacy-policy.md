# Privacy Policy — Claw & Order

**Last updated:** September 5, 2026

Claw & Order is a moderation bot for the thelast.io Discord server. It is operated by server staff, not as a public third-party service.

## What we collect

From **designated public channels only** (not DMs, not voice, not unlisted channels):

- Message text, message ID, channel ID, user ID, display name, timestamp
- Moderation classifications and staff actions (warn / mute / ban)

## How we use it

- Enforce server rules
- Post review items to a **staff-only channel** (staff confirm actions via reactions — no auto-punish from AI alone)
- Keep a local audit trail

Not used for ads, resale, or profiling.

## Storage

- Local SQLCipher-encrypted SQLite database and log files on the bot operator's machine
- Database encryption key is stored in the operator environment (not in the database file)
- Admin UI is **localhost only** — not public internet

## AI

- Optional local inference (Ollama) for classification suggestions only
- **No** training on member messages; inference only, no fine-tuning

## Opt-out

No in-bot toggle. Don't post in monitored channels if you don't want messages reviewed under server rules.

## Contact

Privacy questions: thelast.io Discord staff / developers.

| | |
|---|---|
| Read message content? | Yes, monitored public channels only |
| Store off Discord? | Yes, locally |
| Train AI on it? | No |
| Auto-punish? | No — staff confirm first |
