# 🏔️ Landslide Watch

**AI-Based Early Warning and Landslide Risk Monitoring System in NER**

Smart India Hackathon 2026 — Problem Statement: AI-Based Early Warning and Landslide Risk Monitoring System in NER

🔗 **Live Demo:** https://raksita-priya.github.io/landslide-watch-sih/

---

## Problem

The North Eastern Region (NER) frequently faces landslides, flash floods, and road blockages due to heavy rainfall, fragile terrain, and unplanned hill cutting. Monitoring today is mostly reactive and depends on manual reporting, with no real-time predictive system to warn authorities or communities before disaster strikes.

## Solution

Landslide Watch is an AI-assisted platform that:
- Analyses rainfall, soil moisture, slope, elevation & historical landslide data
- Predicts landslide risk and displays it on a live GIS map
- Lets citizens report hazards (photos, location, description) directly from the field
- Verifies reports through **crowd-confirmation** — once ~5-6 nearby people confirm a report, it's automatically marked ✅ Verified, filtering out false alarms
- Generates warnings for an authority dashboard
- Supports multiple languages (Hindi, Assamese, Bengali) via an in-browser translator

## Features

| Page | What it does |
|---|---|
| `index.html` | Home page with navigation to all modules |
| `map.html` | Interactive Leaflet.js GIS map with colour-coded risk markers |
| `report.html` | Citizen hazard reporting form (type, photo, GPS location, description) |
| `warning.html` | High-risk alert screen showing reason & recommended action |
| `dashboard.html` | Authority dashboard — live stats + crowd-verification on citizen reports |

## Tech Stack

- **Frontend:** HTML, CSS, JavaScript
- **Backend (planned):** Python + Flask
- **AI/ML (planned):** pandas, numpy, scikit-learn
- **GIS Map:** Leaflet.js
- **Database (planned):** SQLite
- **Hosting:** GitHub Pages

## Prototype Status

✅ 5 working pages built & deployed
✅ Crowd-verification for citizen reports (live demo)
✅ Multilingual widget (Hindi, Assamese, Bengali)
🔜 AI risk-prediction model, backend, real data source integration

## Data Sources (planned/reference)

- IMD — rainfall & weather data
- SRTM / DEM datasets — terrain & elevation
- NRSC Landslide Atlas — historical landslide inventories
- NDMA guidelines — landslide risk mitigation

## Team

**[Your Team Name]** — Smart India Hackathon 2026

## Future Scope

- Real AI/ML risk-prediction model trained on official datasets
- Backend + database integration (Flask + SQLite)
- Offline-first sync for low-network areas
- SMS/push notification alerts
- Migrate translator to Google Cloud Translation API (current widget is deprecated Oct 2026)
- Integration with government weather & satellite APIs
