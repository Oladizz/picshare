# 📸 PicShare

> **Mobile-First Picture Posting, Organizing & Permanent Sharing Platform**

PicShare is a lightweight, mobile-first web app that lets you upload, organize, and share your pictures and image files with permanent decentralized links (via IPFS) and smart privacy controls.

---

## 📱 Features

- **Mobile-First Design**: Optimized for smartphones with thumb-zone bottom navigation bar, safe-area support, touch targets (≥44px), and native-style bottom sheet modals.
- **Permanent Decentralized IPFS Storage**: Direct integration with Pinata IPFS gateway for globally accessible, permanent image hosting.
- **Zero Mock Data**: Clean, zero-bloat startup. You only see your own pictures.
- **Smart Albums & Categories**: Organize photos into albums (Camera Roll, Screenshots, Work, Personal, or custom albums).
- **Public vs. Unlisted Sharing**:
  - 🌟 **Public**: Shows in your main vault feed.
  - 🔒 **Unlisted**: Hidden from the feed, only accessible to anyone with the direct share link.
- **Mobile QR Code & 1-Tap Share**:
  - Instant on-screen QR Code for scanning with phone cameras.
  - Copy interactive view link.
  - Native Web Share API integration (WhatsApp, X/Twitter, Telegram, Mail).
  - Download original high-resolution image files.
- **Zero-Dependency Dev Server**: Instant startup with Node.js built-in HTTP module.

---

## 🚀 Quick Start

### 1. Clone the repository
```bash
git clone https://github.com/Oladizz/picshare.git
cd picshare
```

### 2. Run the dev server
```bash
npm run dev
```

Visit `http://localhost:8080` in your browser or smartphone.

---

## 🛠️ Tech Stack

- **Frontend**: HTML5, Tailwind CSS, Lucide Icons, Vanilla JavaScript (zero build step)
- **Backend / Dev**: Node.js zero-dependency HTTP server
- **Storage**: Pinata IPFS Gateway + Local IndexedDB/LocalStorage cache
- **License**: MIT
