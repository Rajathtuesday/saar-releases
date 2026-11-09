# Saar — downloads

Saar is a study helper for online classes on Windows. It listens to your class,
reads what is on your screen, and answers questions with Claude using your own
API key.

This repository holds **only the installers**. The source lives elsewhere.

## Download

**[⬇ Saar-Setup-0.3.9.exe](https://github.com/Rajathtuesday/saar-releases/releases/latest/download/Saar-Setup-0.3.9.exe)** — 13 MB

Or browse [all releases](https://github.com/Rajathtuesday/saar-releases/releases).

## Install

1. Download the `.exe` above.
2. Double-click it.
3. Windows will show a blue **"Windows protected your PC"** box. This is normal —
   the installer is not code-signed yet. Click **More info**, then **Run anyway**.
4. Paste your Claude API key when asked (it starts with `sk-ant-`). You can leave
   it blank and add it later.
5. Saar installs to your own user folder. No administrator password needed.

Get an API key at [platform.claude.com](https://platform.claude.com) under
**API keys**, with a little credit added.

## What you need

- Windows 10 or 11, 64-bit
- About 1.5 GB free space — Saar downloads its speech parts the first time it opens
- An internet connection
- A Claude API key

## If it will not install

**"Windows protected your PC"** — click *More info* → *Run anyway*. This appears
because the installer is unsigned, not because anything is wrong with it.

**"An Application Control policy has blocked this file" (code 4551)** — this
computer is locked down by an administrator and will not run unsigned programs.
Nothing can be done from your side. Try a personal laptop instead.

**The download link does nothing** — some browsers quietly block `.exe` downloads.
Check your Downloads folder, or try a different browser.

**Installed but will not open** — make sure no older copy of Saar is still
running. Open Task Manager, end any `Saar.exe`, then try again.

## Uninstall

Settings → Apps → Saar → Uninstall. Your notes and diaries are kept. Your API key
is removed with the program.
