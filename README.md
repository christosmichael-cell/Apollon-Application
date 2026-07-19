# Apollon Application

Athlete performance tooling for Apollon FC — a static dashboard for reviewing player anthropometrics, performance, and locomotor data, plus a mobile fitness tracker prototype.

## Contents

- **[index.html](index.html)** — Apollon FC Athlete Performance Dashboard. Single-file static HTML app; open directly in a browser. Defaults to dark mode, with a light/dark toggle in the sidebar.
- **[Fitness Tracker.dc.html](Fitness%20Tracker.dc.html)** — "Pulse" fitness tracker mobile app prototype (onboarding, workout log, charts, social, profile), rendered inside an iOS device frame. Depends on [support.js](support.js) and [ios-frame.jsx](ios-frame.jsx).
- **[support.js](support.js)** — Runtime support script for the `.dc.html` component format.
- **[ios-frame.jsx](ios-frame.jsx)** — Reusable iOS device chrome (status bar, nav bar, keyboard) used by the fitness tracker prototype.
- **[Athlete Performance Database.xlsx](Athlete%20Performance%20Database.xlsx)** — Source data backing the dashboard.
- **[OIP.webp](OIP.webp)** — Reference/placeholder image.

## Usage

Open `index.html` or `Fitness Tracker.dc.html` directly in a browser — no build step or server required.

## Notes

- Player photos are excluded from version control (see `.gitignore`).
