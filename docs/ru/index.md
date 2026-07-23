
<div align="center">

# Алексеев Павел

**Разработчик · Студент ПГТУ · Йошкар-Ола**

[![Email](https://img.shields.io/badge/Email-xarizmatv1%40gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:xarizmatv1@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Mr--AKULA-181717?style=flat&logo=github&logoColor=white)](https://github.com/Mr-AKULA)

[🇬🇧 English](./en/)
</div>

---

## Обо мне

Студент направления **Информационные системы и технологии** в ПГТУ (Йошкар-Ола). Строю реальные продукты — от веб-сервисов и Telegram Mini App до Android TV приложений. Предпочитаю разбираться в деталях: архитектура БД, нативная производительность, UX без лишних зависимостей.

---

## Проекты

### [🎬 Found Film Friend](https://github.com/Mr-AKULA/Found-Film-Friend)

> Сервис рекомендаций фильмов с системой друзей. Свайпай карточки, копи список желаний, находи совпадения с друзьями.

**База: 38 000+ фильмов** · [Веб-версия](https://mr-akula.github.io/Found-Film-Friend/) · [Telegram Mini App](https://t.me/MrAKULA_bot) · [Android TV APK](https://github.com/Mr-AKULA/Found-Film-Friend/releases/tag/v1.0-tv)

| Платформа | Статус |
|-----------|--------|
| 🌐 Web App (PWA) | ✅ Live |
| ✈️ Telegram Mini App | ✅ Live |
| 📺 Android TV | ✅ Live |

**Ключевые решения:**

- **Умный алгоритм подбора** — скор фильма = случайность × приоритет × лог(лайки сообщества) × лог(жанровый профиль юзера). Без ML, но реально персонализирует.
- **Система друзей** — инвайт по реферальной ссылке, общий список совпадений, рекомендации между друзьями.
- **Telegram Mini App** — авторизация через Telegram аккаунт автоматически, haptic feedback при свайпах.
- **Android TV** — D-pad управление на всех экранах, фокус-ловушка в модалках, просмотр фильмов прямо в WebView с нативным фуллскрином (`onShowCustomView`), вход через 6-значный pairing-код с телефона.
- **0 зависимостей в рантайме** — весь фронтенд на Vanilla JS, никаких фреймворков.
- **Слияние аккаунтов** — Telegram и браузерный аккаунт объединяются через RPC без потери данных.

**Стек:** Vanilla JS · Python · Java (Android) · Supabase (PostgreSQL + Auth + RPC) · Telegram WebApp API · PWA · Service Worker

---

<!-- Следующий проект добавить сюда по той же схеме -->

---

## Стек

| Категория | Технологии |
|-----------|-----------|
| **Языки** | JavaScript, Python, Java, SQL |
| **Backend / BaaS** | Supabase, PostgreSQL, REST API |
| **Frontend** | Vanilla JS, HTML, CSS, PWA |
| **Mobile / TV** | Android WebView, Telegram WebApp API |
| **Инструменты** | Git, GitHub Actions, adb |

---

## Образование

**ПГТУ** — Поволжский государственный технологический университет, Йошкар-Ола  
Радиотехнический факультет (РТФ)  
09.03.02 Информационные системы и технологии · Очная форма · Группа ИСТ
