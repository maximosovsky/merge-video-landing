# Architecture — merge-video-landing

## Overview

Landing page для Merge Video — сервиса объединения видео из Google Drive, Google Photos и YouTube. Статическая страница, сгенерированная в Umso (no-code builder).

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Generator | Umso (no-code website builder) |
| Fonts | Google Fonts (Lato, Sora) |
| Scroll | SmoothScroll.js |
| Analytics | Umso SendEvent / PageView |
| Deploy | GitHub Pages |

## Project Structure

```
├── index.htm             # Single-page landing (minified HTML)
├── css/                  # Compiled CSS (Umso-generated)
├── css-1                 # Google Fonts CSS
├── lib_hCbTwtypfRFzmFju/ # Images and icons
├── lib_wfKJyoksALKsfAWv/ # Hero images
├── s/                    # Scripts
├── .github/              # GitHub config
└── LICENSE               # MIT
```

## Page Sections

1. **Header** — логотип «Merge Video», кнопки Email Bot + Telegram Bot
2. **Hero** — заголовок + описание, CTAs
3. **Features** — Google Drive, Google Photos, YouTube
4. **Feature Detail** — мобильные скриншоты бота, описание (Telegram Bot, AWS, Card payments)
5. **Footer** — ссылки, соцсети (Telegram, Instagram, YouTube, Product Hunt)

## Key Concepts

- **Fully static** — нет JS-логики, только landing page
- **Umso-generated** — HTML сгенерирован через Umso, не предназначен для ручной правки
- **Two bots** — Email Bot (merge-video.com) и Telegram Bot (@MergeVideo_bot)
