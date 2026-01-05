# YouTube Notifier & Auto Downloader (Windows, CustomTkinter)

Modern GUI tool to watch YouTube channels in real time, send Telegram alerts, and auto-download new videos with yt-dlp. Built with CustomTkinter, pyngrok, and a pre-bundled Windows executable for quick start.

## Key Features
- Real-time YouTube notifications via webhook (ytnoti) with Ngrok tunneling.
- Auto-download new videos with yt-dlp; choose resolution and open the downloads folder in one click.
- Telegram alerts (bot token + chat ID), clickable Telegram contact link in errors.
- Channel management table with per-channel delete buttons.
- Hardware ID + license status display for activation workflows.
- Bundled helpers (`ngrok.exe`, `yt-dlp.exe`) inside `tools/`; fallback download URL override via environment.

## Quick Start
1) Download the latest release (or run `tool_theo_doi_youtube_v1.2.exe` in `tool_theo_doi_youtube_v1.2/`).
2) Make sure `tools/ngrok.exe` and `tools/yt-dlp.exe` exist (provided in release; auto-download if missing).
3) Enter your Ngrok token (required) and optionally Telegram bot token + chat ID.
4) Add channel IDs (comma-separated) in “Follow Channel”, then click “Follow”.
5) Click “Start” to begin listening; logs appear at the bottom. Use “Stop” to halt.
6) For downloads: tick “Download video”, pick quality, and use “Open downloads folder” to view files.

## Configuration Details
- Ngrok: Required to receive webhooks. Token saved to `config.txt`. If missing or empty, saving/starting will show an error.
- Telegram: Optional. Enter bot token + chat ID; alerts will be sent on new uploads.
- Channels: Add multiple IDs separated by commas. The subscribed table shows each channel with a red “Delete” action button.
- Hardware ID & License: Hardware ID is copyable; license status is read-only and gray. It displays after a license check (e.g., “Valid until YYYY-MM-DD” or “Unregistered”).


## Ngrok Download Fallback
- The tool first looks for `tools/ngrok.exe`. If missing, it tries these in order:
  1. `NGROK_DOWNLOAD_URL` environment variable (use your own GitHub mirror if the official link is unstable).
  2. Official Ngrok v3 Windows zip URLs (multiple fallbacks).
  3. Legacy v2 Windows zip as a last resort.
- Set your mirror before launch (example):  
  `set NGROK_DOWNLOAD_URL=https://raw.githubusercontent.com/<user>/<repo>/main/ngrok-v3-stable-windows-amd64.zip`

## Tips & Troubleshooting
- Keep the tool running to receive notifications. Check the log panel for errors.
- Use the “Update yt-dlp” button to refresh the downloader binary when formats change.
- If Ngrok download fails, place `ngrok.exe` manually into `tools/` and restart.
- Telegram contact link in error dialogs is clickable; no “OK” click required to open.

## Keywords (SEO)
YouTube notifier Windows, CustomTkinter GUI, Telegram bot alerts, pyngrok Ngrok webhook, yt-dlp auto download, YouTube channel monitor, real-time YouTube upload alerts, GUI YouTube downloader, Ngrok download fallback, Windows desktop YouTube notifier

