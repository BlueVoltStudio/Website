<div align="center">

<img src="BlueVolt Logo.png" alt="BlueVolt" width="96">

# BlueVolt website

**The home of Gym High Bar: links, legal pages and live service status.**

[![Site](https://img.shields.io/website?url=https%3A%2F%2Fapp.bluevoltstudio.com&label=app.bluevoltstudio.com)](https://app.bluevoltstudio.com)
[![Status](https://img.shields.io/badge/status-live-2ea44f)](https://app.bluevoltstudio.com/status/)
[![Google Play](https://img.shields.io/badge/Google%20Play-Gym%20High%20Bar-414141?logo=googleplay&logoColor=white)](https://play.google.com/store/apps/details?id=com.bluevolt.gymhighbar)
[![App Store](https://img.shields.io/badge/App%20Store-Gym%20High%20Bar-0d96f6?logo=appstore&logoColor=white)](https://apps.apple.com/ca/app/gym-high-bar/id6449169917)
[![GitHub Pages](https://img.shields.io/badge/hosted%20on-GitHub%20Pages-222?logo=github)](https://pages.github.com)

</div>

---

Plain HTML, CSS and JavaScript. No build step: GitHub Pages serves `main` as is.

| Path | What |
|---|---|
| `index.html` | Hub page: store links, privacy policy, terms. Strings in `strings.js` (English, Russian, Japanese). |
| `status/` | Status page. Reads `status.json` from the `status-data` branch, which the backend uptime workflow updates. |
| `app-ads.txt` | Ad network seller list. |

Preview locally with any static server, for example `python -m http.server`.
