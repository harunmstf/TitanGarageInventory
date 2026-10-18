# Моят гараж — локален инвентар

Bulgarian-language, phone-first PWA. Inventory and history are stored locally in the browser's localStorage. No accounts, cloud backend, analytics, or network API calls.

## Quick deploy (for Android installation)
A PWA must be served from HTTPS to install reliably. Upload these files to a private or public GitHub repository and enable GitHub Pages, or deploy with Firebase Hosting. GitHub Pages is usually the simplest for a static app, but anyone who knows the URL can open the app; the data itself remains in each browser/device.

## Notes
- Data is stored per browser/device and is not synchronized.
- Export a JSON backup regularly using the Архив tab.
- Clearing browser/site data may delete inventory.
- Service worker caches the app shell for offline opening after the first visit.
