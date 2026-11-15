# Pump Performance Toolkit

Field web app for terminal operations and maintenance teams, based on the Pump Performance Standard Procedure (Wafi Energy Pakistan Limited).

- Inspection records: Annex A (surveillance) and Annex B (technical) with automatic status, save, print and CSV export
- Condition checks: vibration (ISO 10816), bearing temperature, motor load, operating point
- Calculators: total head from gauges, static/system head, NPSH available, power and efficiency, affinity laws, unit converter
- Planning: inspection frequency by pump class, criticality classes, KPI calculator (MTBF, MTTR, availability)
- Guides: troubleshooting, start-up and shutdown checklist, acceptance criteria, reference and the full procedure PDF

It is a static site (no server, no build step). Records are stored only in the browser of the device used.

## Publish with GitHub Pages
Repository **Settings → Pages → Build and deployment → Deploy from a branch →** `main` / `/ (root)`.
