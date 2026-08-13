# Telegram Music Bot

A Telegram group voice-chat music bot project scaffold.

## Included

- `requirements.txt` with Telethon, PyTgCalls, yt-dlp and dotenv
- `.env.example` for local configuration
- `.gitignore` to keep local secrets and Telegram session files out of Git
- `Dockerfile` with FFmpeg

## Commands planned

- `/play`
- `/pause`
- `/resume`
- `/skip`
- `/stop`
- `/queue`
- `/now`

## Runtime requirements

- Python 3.10+
- FFmpeg
- Telegram API credentials
- Telegram bot token
- A separate Telegram user session used by the voice-call client

Never commit real tokens, API hashes, or session strings to GitHub. Put them only in your local `.env` or your hosting provider's secret/environment settings.
