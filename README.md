<div align="center">

# 🌐 Kian CDN Netlify

### VLESS+XHTTP relay through Netlify's global CDN

**🇮🇷 [راهنمای فارسی پایین‌تر صفحه](#راهنمای-فارسی)** — Persian guide below

[![Live Site](https://img.shields.io/badge/Live%20Site-Open%20in%20Browser-3fb950?style=for-the-badge&logo=github)](https://KIAN-IRANI.github.io/Kian-CDN-Netlify)
[![Telegram](https://img.shields.io/badge/Telegram-Channel-26A5E4?style=for-the-badge&logo=telegram)](https://t.me/kian_irani_cdn_f)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](LICENSE)
[![Stars](https://img.shields.io/github/stars/KIAN-IRANI/Kian-CDN-Netlify?style=for-the-badge&color=yellow)](https://github.com/KIAN-IRANI/Kian-CDN-Netlify/stargazers)

</div>

---

## ⚡ What is this?

A complete setup guide for relaying **VLESS+XHTTP** (V2Ray/Xray) traffic through **Netlify's global CDN**.

Your ISP only sees a normal HTTPS connection to a CDN edge — no VPN signature, no proxy fingerprint, no easy way to filter.

### How it works

```
📱 User (Iran)
    ↓  VLESS+XHTTP over TLS
🌐 Netlify Edge Function  (cannot be filtered)
    ↓  HTTP relay
🖥️  Your VPS  (3x-ui + Xray)
    ↓
🌍 Free internet
```

---

## ✨ Why this method?

- 🆓 **Free Netlify CDN** — generous free tier
- 🌍 **Global edge** — automatic routing to nearest PoP
- ⚡ **XHTTP transport** — designed for HTTP CDN resilience
- 🛡️ **Hidden behind CDN** — IP of your VPS never exposed
- 🔐 **Standard TLS** — no custom protocol, no DPI fingerprint

---

## 🚀 Quick Start

The setup is **fully interactive** — visit the live site:

### 👉 [kian-irani.github.io/Kian-CDN-Netlify](https://KIAN-IRANI.github.io/Kian-CDN-Netlify)

Fill in your VPS IP, port, and credentials → get ready-to-use configs.

---

## 📋 Requirements

### VPS
- Any provider (Iran-friendly recommended)
- 1 vCPU, 512MB RAM minimum
- Ubuntu/Debian
- 3x-ui or Xray-core installed

### Client
- Android: V2RayNG or NekoBox
- Windows: V2RayN or NekoRay
- iOS: Shadowrocket

---

## 🆘 Support

- 💬 Telegram: [@Kian_irani_t](https://t.me/Kian_irani_t)
- 📢 Channel: [@kian_irani_cdn_f](https://t.me/kian_irani_cdn_f)

---

## 📄 License

MIT — see [LICENSE](LICENSE)

---

<div align="center">

## راهنمای فارسی

</div>

### 🌐 Kian CDN Netlify — رله اینترنت آزاد

راهنمای کامل راه‌اندازی **VLESS+XHTTP** از طریق **Netlify CDN**.

ترافیک از طریق **CDN جهانی Netlify** رد می‌شه. ISP فقط یه اتصال HTTPS عادی به یه سایت می‌بینه — نه VPN، نه پروکسی.

### 🚀 شروع سریع

به **[صفحه تعاملی](https://KIAN-IRANI.github.io/Kian-CDN-Netlify)** برو — همه چیز رو با مراحل تصویری توضیح می‌ده.

### 💬 ارتباط

- 💬 پشتیبانی: [@Kian_irani_t](https://t.me/Kian_irani_t)
- 📢 کانال: [@kian_irani_cdn_f](https://t.me/kian_irani_cdn_f)

---

<div align="center">

⭐ **Star this repo** if it helped you!

</div>
