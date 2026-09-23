# Landslide Watch

**AI-Based Landslide Early Warning & Risk Monitoring System for North East Region (NER), India**

Built for Smart India Hackathon (SIH) 2026.

## Overview

Landslide Watch is a web-based prototype that monitors landslide risk across the North East Region of India. It combines historical environmental data with a simple risk-visualization map to help communities and authorities identify vulnerable zones and respond to hazards faster.

## Features

- **Risk Map** — Interactive map showing landslide risk levels (Low / Moderate / High / Critical) across NER, with rainfall, elevation, slope, and susceptibility data in each location's popup.
- **Report Hazard** — Lets users report a landslide hazard they observe.
- **Current Warnings** — Displays active landslide warnings.
- **Risk Status Dashboard** — Overview of current risk status.
- **Multi-language support** — Site can be viewed in Hindi, Assamese, Bengali, and Manipuri (Meitei) via one-click translation links.

## Data Sources

- **Rainfall data** — India Meteorological Department (IMD)
- **Elevation & slope data** — SRTM (Shuttle Radar Topography Mission), via Bhuvan/OpenTopography
- **Landslide susceptibility** — National Remote Sensing Centre (NRSC), ISRO

*Note: Sample/reference values are used for this prototype demo. Live API integration with these sources is planned as future scope.*

## Tech Stack

- HTML, CSS, JavaScript
- [Leaflet.js](https://leafletjs.com/) for interactive mapping
- OpenStreetMap for map tiles
- Google Translate for multi-language support
- Hosted on GitHub Pages

## Live Demo

https://raksita-priya.github.io/landslide-watch-sih/

## Future Scope

- Live integration with IMD, SRTM, and NRSC APIs for real-time data
- AI/ML-based landslide risk prediction model
- SMS/push notification alerts for at-risk communities
- Mobile app version

## Team

Built by Raksita Priya and team for Smart India Hackathon 2026.