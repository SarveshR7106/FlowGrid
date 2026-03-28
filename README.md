# FlowGrid — Traffic Command Dashboard

FlowGrid is a browser-based traffic monitoring and control dashboard
built entirely with HTML, CSS, and vanilla JavaScript.
No backend, no build step — just open and run.

---

## Pages

| File | Description |
|------|-------------|
| `index.html` | Login screen. Demo: `admin` / `traffic123` |
| `home.html` | Main dashboard — KPIs, live map, incident feed |
| `map.html` | Full-screen Leaflet world map with city search |
| `window_2_kpi_cards.html` | KPI deep-dive, zone charts, 7-day trend |
| `window_3_field_units.html` | Field unit tracking |
| `window_4_incidents.html` | Incident list with filter, acknowledge, resolve |
| `window_5_signal_nodes.html` | Per-junction signal status |
| `window_6_flow_chart.html` | Hourly throughput bar charts |
| `window_7_sensor_health.html` | Sensor status with ring chart |

---

## Running It

Just open index.html in any browser.
Navigate between pages using the sidebar.

---

## Stack

- HTML / CSS / Vanilla JS
- Leaflet.js v1.9.4 (world map)
- Google Fonts — Syne, DM Mono, Instrument Sans
- Canvas API (city traffic overlay)

All data is simulated in-browser. KPI counters update every 3 seconds,
incident states persist per session.

---

## Credentials

Username : admin
Password : traffic123

Or hit "Enter with Demo Credentials" on the login page.

---

## Deployment Link
Vercel Deployed link: https://flow-grid-three.vercel.app/