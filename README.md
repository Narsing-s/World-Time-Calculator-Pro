# 🌍 World Time Pro

A polished, responsive **world clock + timezone intelligence app** for people working across countries and time zones.

**Live app:** https://world-time-calculator-pro.vercel.app  
**Repository:** https://github.com/Narsing-s/World-Time-Calculator-Pro

## ✨ What changed

- Premium glassmorphism dashboard with responsive mobile-first layout
- Live local clock with current UTC offset
- Search across the browser's IANA timezone database
- Favorites with persistent localStorage
- Day/night filters
- Real-time clocks updated every second
- Exact timezone conversion with source/target context
- Quick time presets: now, next work hour, next midnight
- One-click share / copy link
- Dark/light mode persisted locally
- Offline-ready PWA service worker
- No API key, backend, database, or paid service required

## 🧭 Use cases

- Global engineering and production-support teams
- Remote teams scheduling meetings
- Travel and international communication
- API/integration operations across regions
- Developers validating timezone and DST behavior

## 🛠️ Architecture

This is intentionally lightweight: HTML/CSS/JavaScript using the browser's native Intl.DateTimeFormat and IANA timezone data. Favorites and preferences use localStorage.

## 🚀 Deployment

The project is static and can be deployed directly to Vercel, GitHub Pages, Cloudflare Pages, Netlify, or any static host.

## 📱 PWA

manifest.json and sw.js provide install/offline support. The app continues to work without an external time API.

## 📄 License

MIT
