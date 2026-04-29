# 🔵 Indeed Job Search

A clean, client-side Indeed job search filter tool — no logins, no tracking, no ads.

Build a filtered Indeed job search URL instantly and open it directly in your browser.

**[🔎 Live Demo →](https://rejaul-rajib.github.io/indeed-filters/)/**

---

## Features

- **Keyword & location** search fields
- **Date posted** — Past 24 hours, 3 days, week, 2 weeks, or month
- **Sort** by relevance or date posted
- **Search radius** — 5 to 100 miles from your location *(Indeed-exclusive)*
- **Posting source** — Direct from employer or job boards only *(Indeed-exclusive)*
- **Salary estimate** filter ($40k – $200k+)
- **Experience level** — Entry, Mid, or Senior
- **Job type** — Full-time, Part-time, Contract, Temporary, Internship
- **Remote only** toggle
- **Quick filter cards** — one-click presets:
  - Past 24 Hours
  - Past 3 Days
  - Remote Only
  - Nearby (25 mi)
  - Direct Employer
  - Reset All
- **Live URL preview** with one-click copy button
- **Light / Dark mode** toggle (respects system preference)

---

## Usage

1. Open `index.html` in any modern browser — no server or build step required
2. Fill in your keyword and location
3. Apply any filters
4. Click **Search Indeed Jobs** to open results, or copy the URL to share

---

## How It Works

All filtering is done by constructing an Indeed search URL with query parameters and opening it in a new tab. Nothing is stored, sent, or tracked — everything runs entirely in your browser.

**Key URL parameters used:**

| Parameter | Description |
|---|---|
| `q` | Job title or keyword |
| `l` | Location (city, state, zip code) |
| `sort` | `relevance` or `date` |
| `fromage` | Days since posted (1, 3, 7, 14, 30) |
| `radius` | Distance in miles (5, 10, 15, 25, 50, 100) |
| `st` | Source: `employer` (direct) or `jobsite` (boards) |
| `salary` | Salary estimate string (e.g. `$80,000+`) |
| `explvl` | Experience: `entry_level`, `mid_level`, `senior_level` |
| `jt` | Job type: `fulltime`, `parttime`, `contract`, etc. |
| `remotejob` | `1` = Remote jobs only |

---

## Sister Projects

> Also check out the job search tools for other platforms:
> - 🔗 [LinkedIn Job Search](https://rejaul-rajib.github.io/linkedin-filters/)

---

## License

MIT — free to use, modify, and share.
