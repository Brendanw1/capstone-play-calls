# VT Men's Basketball — Sideline Analytics

A single-page, in-browser analytics console for VT MBB play-calls. It reads live and historical possessions from **Firebase Realtime Database** and renders in-game and post-game views (top plays, outcome distributions, PPP/FG% comparisons, heatmaps, scatter, and radar profiles). Built with **React (UMD + Babel in-browser)**, **TailwindCSS**, and **Chart.js**—no build step required.

---

## Quick Start

1. **Clone** the repository, then open `analytics.html` in any modern browser.
2. To avoid CORS/local file issues, serve it with a lightweight server:
   ```bash
   # pick one
   python -m http.server 8080
   npx http-server -p 8080