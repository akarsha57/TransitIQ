# TransitIQ — SIH 2026

**Team #ArtisanX · Bhopal Pilot Corridor**

TransitIQ is a smart-city mobility prototype that uses public buses as moving road-health sensors. The dashboard demonstrates road-issue detection, geolocation, prioritisation, response assignment, live fleet monitoring, route planning, analytics, alerts and resolution tracking.

> This repository contains the prototype/demo implementation. Data shown in the interface is sample/simulated data unless otherwise stated in the application.

## Features

- 🚌 Live fleet dashboard and simulated bus movement
- 📷 Road-condition detection workflow
- 🗺️ City map with buses, detections and routes
- 🛣️ Road-health monitoring and hotspot logic
- 🚦 Priority classification for detected issues
- 🧑‍🔧 Department assignment and response workflow
- 📊 Analytics and detection history
- 🔔 Alerts and resolution tracking
- 🌙 Dark/light theme support
- 🎬 Built-in demo mode for presentations

## Issue types represented

- Pothole
- Garbage
- Broken Streetlight
- Faded Road Marking
- Damaged Road Sign

## Tech used

The current prototype is delivered as a single static HTML file and loads these libraries from CDNs:

- React 18
- ReactDOM 18
- Recharts
- Lucide React
- Leaflet

The prototype does not require `npm install` or a local build process.

## Run locally

### Option 1 — Open directly

Download or clone the repository and open `index.html` in a modern browser.

### Option 2 — Use a local server

For the most reliable browser behaviour, serve the folder with any simple static HTTP server, for example:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## GitHub Pages

This repository is suitable for GitHub Pages because the application is a static `index.html` file.

1. Push the repository to GitHub.
2. Open **Settings → Pages** in the repository.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and `/ (root)` folder.
5. Save and wait for GitHub Pages to publish the site.

## Project structure

```text
TransitIQ-GitHub/
├── index.html
├── README.md
└── .gitignore
```

## Demo note

TransitIQ includes simulated detections, bus movement, route behaviour and response workflows for demonstration purposes. It should not be presented as a production road-monitoring system without the corresponding backend, trained computer-vision model, live vehicle data, mapping/routing infrastructure and operational integrations.

## Team

**#ArtisanX — SIH 2026**

Project: **TransitIQ**

Pilot corridor: **Bhopal**
