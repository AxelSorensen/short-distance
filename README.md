# 💌 Short Distance

A small installable PWA meant to host little apps and games for staying connected over a long-distance relationship.

![Short Distance screenshot](docs/screenshot.png)
*The screenshot is blank because `FrontPage.vue` is still an empty component (see Status below) — no environment variables are involved, this app doesn't read any.*

## Features

- 📱 **Installable PWA** — configured with `vite-plugin-pwa` and a service worker for offline/home-screen use
- 🐸 **App launcher grid** — a home screen listing mini-apps (currently "The Wide Mouthed Frog") with room for more
- 🎨 **Tailwind styling** — simple utility-first layout

## Installation

```bash
git clone <this repo>
cd short-distance
npm install
```

## Usage

```bash
npm run dev
```

Then open the printed local URL. `npm run build` produces a production build (also deployed to GitHub Pages at the `homepage` URL in `package.json`).

## Built with

- [Vue 3](https://vuejs.org/) + [Vite](https://vitejs.dev/)
- [vite-plugin-pwa](https://vite-pwa-org.netlify.app/)
- [Tailwind CSS](https://tailwindcss.com/)

## Status

🚧 Very early/inactive — the app grid shows one placeholder entry and a "More to come..." tile; `FrontPage.vue` is still empty. Last touched January 2025.

✅ Runs cleanly — `npm install && npm run build` verified working as of 2026-09-03. No credentials required.
