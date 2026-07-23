<div align="center">

# Alekseev Pavel

**Developer · Student of PSTU · Yoshkar-Ola**

[![Email](https://img.shields.io/badge/Email-xarizmatv1%40gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:xarizmatv1@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Mr--AKULA-181717?style=flat&logo=github&logoColor=white)](https://github.com/Mr-AKULA)

[🇬🇧 Russian](../ru/index.md)
</div>

---

## About me

Student of the direction **Information Systems and Technologies** at the Moscow State Technical University (Yoshkar-Ola). I build real products, from web services and Telegram Mini App to Android TV apps. I prefer to understand the details: database architecture, native performance, UX without unnecessary dependencies.

---

## Projects

### [🎬 Found Film Friend](https://github.com/Mr-AKULA/Found-Film-Friend)

> Movie recommendation service with a friends system. Swipe the cards, copy the wish list, find matches with your friends.

**Database: 38,000+ movies** · [Web version](https://mr-akula .github.io/Found-Film-Friend/) · [Telegram Mini App](https://t.me/MrAKULA_bot) · [Android TV APK](https://github.com/Mr-AKULA/Found-Film-Friend/releases/tag/v1.0-tv)

| Platform | Status |
|-----------|--------|
| 🌐 Web App (PWA) | ✅ Live |
| ✈️ Telegram Mini App | ✅ Live |
| 📺 Android TV | ✅ Live |

**Key decisions:**

- **Smart selection algorithm** — movie score = randomness × priority × log(community likes) × log(user's genre profile). No ML, but it really personalizes.
- **Friends system** — invite by referral link, general list of matches, recommendations between friends.
- **Telegram Mini App** — authorization via Telegram account automatically, haptic feedback during swipes.
- **Android TV** — D-pad control on all screens, focus trap in modals, watching movies directly in WebView with native fullscreen ('onShowCustomView'), login via a 6-digit pairing code from your phone.
- **0 runtime dependencies** — the entire frontend is based on Vanilla JS, no frameworks.
- **Merge accounts** — Telegram and browser account are combined via RPC without data loss.

**Stack:** Vanilla JS · Python · Java (Android) · Supabase (PostgreSQL + Auth + RPC) · Telegram WebApp API · PWA · Service Worker

---

<!-- Add the next project here according to the same scheme -->

---

## Stack

| Category | Technology |
|-----------|-----------|
| **Languages** | JavaScript, Python, Java, SQL |
| **Backend / BaaS** | Supabase, PostgreSQL, REST API |
| **Frontend** | Vanilla JS, HTML, CSS, PWA |
| **Mobile / TV** | Android WebView, Telegram WebApp API |
| **Tools** | Git, GitHub Actions, adb |

---

## Education

**PSTU** — Volga State Technological University, Yoshkar-Ola  
Faculty of Radio Engineering (RTF)
09.03.02 Information Systems and Technologies · Full-time · IST Group
