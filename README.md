# 🟣 Stake Drop Telegram Tool – Windows (.exe) Version

A lightweight Windows tool that automatically detects Stake drop codes from Telegram and opens them in your browser — fast and easy.

## ⚙️ Features

- 🔍 Automatically detects Stake drop codes.
- 🌐 Opens the drop links in your default web browser.
- 📬 Connects securely to your Telegram account.
- 🖥 Clean and simple user interface.

## 📦 How to Use (Quick Setup)

1. Download the file: `StakeDrop.exe`
2. Double-click to launch it (no installation needed).
3. The app will ask for:
   - Your Telegram API ID
   - Your API Hash
   - Your Telegram phone number

## 🔐 How to Get Your Telegram API ID & Hash

1. Go to: [https://my.telegram.org](https://my.telegram.org)
2. Log in using your phone number
3. Click **API Development Tools**
4. Fill out the form:
   - App Title: for example `StakeDropTool`
   - Short Name: `stakeapp`
5. After submitting, you’ll get:
   - API ID (a number)
   - API Hash (a long string)

💡 You only need to enter these once — the app will save them securely for future use.

## 🔔 Join These Telegram Channels

To receive Stake drop codes, make sure you’ve joined the following public channels:

- ✅ RainsTEAM
- ✅ StakecomDailyDrops

These are the channels monitored by the app.

## ✅ App Behavior

Once configured and started:

- It connects to Telegram in the background.
- It watches for new drop codes from the two channels.
- When a new code is detected:
  - It displays the code in the app window.
  - It opens the drop link in your browser:  
    `https://stake.bet/?drop=YOURCODE`

## 🖥 Interface Overview

- **Start Telegram:** Begins monitoring the channels.
- **Stop:** Stops monitoring (restart required to resume).
- **Open in browser:** Automatically opens drop links when checked (default: enabled).

## 💾 Saved Data

Your credentials (API ID, Hash, and phone number) are stored locally in a file named `config.json`, located in the same folder as the `.exe`. You won’t need to re-enter them every time.

## 🛡 Security & Privacy

- Your information is stored only on your device.
- The app uses the official Telegram API.
- No data is transmitted outside of Telegram’s secure infrastructure.

## 🔧 Troubleshooting

- If you entered the wrong info and need to start over:
  1. Close the app.
  2. Delete the file `config.json`.
  3. Re-launch the `.exe` and re-enter your credentials.
- If the app doesn’t open or shows an error:
  - Check your internet connection.
  - Make sure your firewall or antivirus isn’t blocking the app.
  - Try running the `.exe` as Administrator.

## 📁 Included Files

- `StakeDrop.exe` – portable Windows executable (No installation required)
