# PocketOS

PocketOS is a personal mini operating system running entirely in the browser: a polished Y2K desktop for notes, tasks, calendar events, money tracking, links, focus sessions, imported files, and utilities.

## Features

- Desktop shell with glossy Y2K visual language, icons, widgets, Start menu, taskbar, notifications, themes, wallpapers, CRT mode, and responsive mobile layout.
- Window controls: open, close, minimize, maximize, foreground focus, and taskbar switching.
- Functional Notes, Tasks, Calendar, Money, Links, Focus, Files, Calculator, Settings, and About apps.
- Global search with `Ctrl + K`.
- Local persistence using browser storage with an IndexedDB write-through cache; no accounts, backend, API keys, or external database.
- PWA manifest and offline service-worker shell.

## Run locally

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
npm run preview
```

The `dist` folder is a static SPA and can be deployed to Vercel or any static host. No environment variables are needed.

## Privacy and data

PocketOS stores user data on the current device only. The Files app only sees files explicitly imported through the browser file picker. Settings includes an export backup action. Clearing data is intentionally explicit and reloads the application.

## Technology

React 19, TypeScript, Vite, custom CSS, IndexedDB-compatible browser persistence, and PWA assets.
