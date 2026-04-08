# ENSO OPS — Derek Command Centre

> **Single-file operations dashboard for Derek's consultancy role at ENSO / SPARK.**
> Built for daily execution, CRM, pipeline management, and commission tracking.

---

## What This Is

A fully offline, single-HTML-file operations system that runs in any browser with zero dependencies or installs. All data is saved in localStorage on the device.

Built specifically for the ENSO consultant role covering:
- SPARK Wellness Studio (Jaffery Sports Club, Lavington)
- Entim Sidai (Karen)

---

## Sections

| Section | Purpose |
|---|---|
| **Dashboard** | Live snapshot — today's targets, 7-day booking chart, follow-up queue, pipeline summary |
| **Daily Checklist** | Non-negotiable daily counters: responses, 20 outbound, 10 follow-ups, 2 bookings + message templates |
| **Contacts** | CRM — status tracking (New Inquiry → Follow-Up → Confirmed), source, notes |
| **Bookings** | Log every booking closed, mark no-shows, track monthly count & revenue |
| **Partnerships** | 4-stage Kanban pipeline: Visited → Pitched → Negotiating → Active |
| **Jumia Sales** | Product performance tracker + listing health checklist |
| **Events** | Event log with attendee count, content capture status, 24hr follow-up tracking |
| **EOD Report** | End-of-day report builder with WhatsApp copy |
| **Earnings** | Commission calculator — base + bookings + partnerships + Jumia bonus |

---

## Live Deploy (GitHub Pages)

1. Fork or upload this repo to GitHub
2. Go to **Settings → Pages → Source → main branch / root**
3. Your dashboard will be live at `https://[your-username].github.io/enso-ops/`
4. Bookmark it on your phone's home screen

---

## How to Use Daily

### Morning (8:00 – 8:30 AM)
1. Open **Dashboard** → check overnight inquiries
2. Open **Daily Checklist** → start counting responses
3. Send availability updates → tick the box

### Midday
4. Hit 10 outbound messages by noon (counter in Daily)
5. Process Jumia orders (tick checklist in Jumia tab)
6. Log any bookings immediately after closing

### Afternoon (Outreach Days)
7. Open **Partnerships** → log every location visited → advance stage after pitch
8. Follow up within 48 hours → update notes

### Evening
9. Open **EOD Report** → fill all fields → copy to WhatsApp → send to ENSO line
10. Verify day score is 6/6 in Daily Checklist

---

## Monthly Targets

| Target | Minimum | Stretch |
|---|---|---|
| Bookings | 40 | 60 |
| Partnerships | 8 | 12 |
| Projected Pay | KES 55,000 | KES 71,000+ |

Commission = **KES 500 per confirmed booking** on top of KES 35,000 base.

---

## Tech Stack

- Pure HTML + CSS + Vanilla JS
- Chart.js (CDN) for booking trend chart
- Google Fonts (DM Sans, Bebas Neue, DM Mono)
- **localStorage** for all data persistence (no backend, no login, works offline)

---

## Data Backup

Since data lives in localStorage, export a backup periodically:

Open browser console and run:
```js
copy(localStorage.getItem('enso_ops_v1'))
```
Paste into a Google Doc or Notes app to keep a backup.

---

## File Structure

```
enso-ops/
├── index.html    ← entire app (single file, self-contained)
└── README.md     ← this file
```

---

*Built for ENSO Consultancy & Services Ltd. — Nairobi, Kenya*
