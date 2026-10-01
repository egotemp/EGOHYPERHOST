# EGO Hosting Bot v3.5

Telegram bot hosting platform — users .py / .js / .zip files upload, host, control.

## Features
- Owner approval system
- Terminal access (OTP)
- Auto-restart on crash
- Referral system
- Health monitor
- Railway ready

## Deploy
1. Fork / clone this repo
2. Railway.app → Deploy from GitHub
3. Add env vars: `BOT_TOKEN`, `OWNER_ID`, `PYTHONUNBUFFERED=1`
4. Add Volume: `/app/EGO_data`, `/app/EGO_uploads`
5. Done.

## Commands
- `/start` — welcome
- `/help` — commands
- Upload file → approval → host

## Credits
- EGO HOSTING BOT V3.5
- TITAN CODER + OMEGA UPGRADE