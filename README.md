# Kanai Executive Management Portal

Central landing page for all Kanai's Roll Off internal management tools, reporting systems, and analytics dashboards.

**Live:** https://kanai-executive-portal.vercel.app

## Applications

### Operations & Reporting
- **Field Supervisor EOD Form** — End-of-day reporting for field supervisors. Tracks truck performance, dump runs, team members, sales, and closing percentages for junk removal and dumpster rental divisions.
- **CSR End-of-Day Report** — Structured daily reporting for customer service reps. Tracks call metrics, dispositions, booking rates, follow-ups, and auto-calculates KPIs with bonus eligibility.

### Analytics & KPIs
- **Ops Director KPI Dashboard** — Comprehensive analytics for the Director of Operations. Executive summary, KPI analysis, bonus calculator, team performance rankings, and dumpster rental metrics.

### Field Tools
- **Junk Estimator Tool** — Mobile-first truck load estimator. Camera capture, fill level estimation for 15-yard trucks, and text message sharing.
- **Tech Schedule** — Field technician scheduling, crew assignments, and dispatch optimization.

### HR & People
- **Attendance Tracker** — Employee attendance tracking with tardies, absences, no-call/no-shows, and progressive discipline points.

### Events & Marketing
- **Expo Sign-In & Lead Capture** — Trade show lead capture form with Google Sheets integration and raffle tracking.

## Tech Stack

- Static HTML/CSS (no build step)
- Outfit + Poppins fonts (matching kanaisjunkremoval.com brand)
- Kanai red (#E41D2D) accent on dark theme
- Deployed on Vercel

## Development

Open `index.html` directly in a browser, or serve locally:

```bash
npx serve .
```

## Deployment

```bash
npx vercel --prod --yes
```
