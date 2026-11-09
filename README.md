# CoolSight — Cooling Tower Monitoring Panel (Stakeholder Demo)

## Open
Double-click `index.html` in any modern browser. No server, dependencies, build command or internet connection is needed for the application behavior. The optional Google Fonts import requires internet; if offline the interface uses system fonts.

## Functional pages
- **Overview:** asset KPI cards, example trend, recent activity, fleet cards, anomaly simulation.
- **Cooling Towers:** filter/search, asset detail modal with readings and open alerts, add demo asset.
- **Alert Center:** search/filter, acknowledge, generate simulated vibration alarms, open prefilled maintenance orders.
- **Maintenance:** assign/create work orders, progress from open to in progress to completed.
- **Analytics:** choose tower, inspect illustrative trend, approach and cooling range, operating metrics.
- **Reports:** export four real CSV datasets generated from the browser's current demo state, print to PDF.
- **Settings:** update facility name, notification display email, demo alarm thresholds, reset demo.

Demo changes are saved in `localStorage` in the browser. Browser storage is not shared with other users. Use Reset demo data to return to the initial view.

## Important limitations
**This is a clickable frontend prototype, not a production monitoring system.** No sensors, MQTT, PLC/SCADA, persistent backend/database, authentication, real alert delivery, predictive ML model, or validated operating limits are implemented. Readings are fictitious. Engineering judgement, calibrated sensors, and site-specific water-management safety programs are necessary before industrial use. The displayed efficiency is an illustrative demo index, not a measured thermodynamic efficiency.

## Hosting
Upload `index.html`, `styles.css`, and `app.js` together to any static website hosting platform. No secrets or API keys are needed.
