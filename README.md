# SEAT 2.0 interactive front-end prototype

This is a static, responsive interface prototype for the Nigeria Civil Society Situation Room's SEAT platform. It demonstrates the intended product structure and interaction patterns for an IT and product team.

## Run it

Open `index.html` in a current desktop or mobile browser. The prototype has no package installation or build step. For a local web server, run `python3 -m http.server 8000` from this directory and open `http://localhost:8000`.

## Included views

- Public accountability overview with reform, scorecard and citizen experience entry points
- Reform Tracker with clickable KPI filters, institution filters, search, theme filters and recommendation detail records
- Recommendation profile with summary, evidence trail, timeline and citizen experience tabs
- Stakeholder scorecards with institution tabs and illustrative indicator values
- Citizen Experience dashboard and Election Day Observatory with a map-style report distribution, indicator view and channel view
- Multi-step citizen report form with required state and consent validation
- Member organisation network dashboard with readiness summaries and a searchable directory
- Evidence archive with search and evidence detail drawers
- Events calendar and event detail drawers
- Responsive navigation and mobile layouts

## Demo data and production boundary

All counts, institution scores, map marks, dates, events, evidence records and recommendation statuses are illustrative demo data. The prototype does not connect to SEAT, accept network submissions, authenticate users or persist survey responses beyond the open browser session. The interface uses Google Fonts when a connection is available and falls back to local sans-serif fonts otherwise.

## Source files

- `index.html`: semantic page structure and entry point
- `styles.css`: identity, layout, responsive behaviour and component styling
- `app.js`: demo data, view routing and interactions
