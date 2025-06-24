# 🗂️  FTP Backup

This repository automatically backs up files from my personal  server's SFTP every **6 hours** using GitHub Actions.

> 🧪 **Personal Use Only**  
> This backup system is maintained by [@aloramiaa](https://github.com/aloramiaa) for **private server maintenance and recovery**.  
> Feel free to peek, fork, or learn — but please don’t rely on it as a public backup service. 😉

---

## 📦 Latest Backup Download

[![Latest Release](https://img.shields.io/github/v/release/aloramiaa/-Backup?label=Latest%20Backup&style=for-the-badge&color=blue)](https://github.com/aloramiaa/-Backup/releases/latest)

---

## 🔁 What This Repo Contains

- 🔄 Automatically synced files from `sftp://delta.optiklink.com:2022`
- 📁 All content stored in the `ftp-backup/` folder
- 📦 `.zip` archives attached to every [GitHub Release](https://github.com/aloramiaa/-Backup/releases)

---

## ⚙️ How It Works

1. Runs every 6 hours (or manually via [Actions tab](../../actions))
2. Uses `lftp` to securely download files from your FTP server
3. Commits updates to the repo (excluding ignored files like `README.md`)
4. Creates a `.zip` archive and publishes it as a GitHub Release
5. Sends a friendly notification to Discord

---

## 🛠️ Built With

- 🏗️ [GitHub Actions](https://github.com/features/actions)
- 🔐 `lftp` for SFTP mirroring
- 📬 Discord Webhook for logs
- 💾 ZIP releases for downloadable archives

---



