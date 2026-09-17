# Timeline-Teller V1

A privacy-first web/PWA app for analyzing a Google Maps Timeline JSON export.

Features:
- Detect first and last date in the JSON
- Select any date range
- Total distance, journeys and travel time
- Time spent at places, aggregated over the selected range
- Repeated journey detection and counts
- Map route display and route highlighting
- Name regular/repeated trips
- Fuel price + mileage calculator
- Daily reminder permission UI
- Local JSON processing; do NOT upload Timeline.json to GitHub

Important:
- The map uses Leaflet + OpenStreetMap tiles and needs internet access.
- Browser background notifications are not guaranteed at an exact daily time. A native Android version can provide a more reliable scheduled notification.
