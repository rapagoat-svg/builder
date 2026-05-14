# 🚀 BotBuild Manager

Bot Telegram untuk build APK dari project Flutter via GitHub Actions & setup VPS via SSH.

## ✨ Fitur

- 📦 **/buildapk** - Build APK dari file ZIP project Flutter (via GitHub Actions)
- 🔧 **/botbuild** - Setup build environment di VPS baru (via SSH)
- 📊 **/status** - Cek status build APK
- ❌ **/cancel** - Batalkan build yang sedang berjalan
- 🔗 **/setpanel** - Set URL panel (untuk custom endpoint)
- 📡 **/testpanel** - Test koneksi ke panel

## 📋 Prasyarat

- Node.js v16 atau lebih tinggi
- Bot Token dari [@BotFather](https://t.me/BotFather)
- GitHub Token (untuk GitHub Actions)
- Repository GitHub untuk workflow build

## 🚀 Instalasi

### 1. Clone repository

```bash
git clone https://github.com/rapagoat-svg/builder.git
cd builder# builder
