SM GATE EXCHANGE — zero-cost PWA starter

Files:
- index.html: app UI and logic
- manifest.json: installable web app metadata
- service-worker.js: caches app files for offline use after first successful load
- icons/: app icons

What works:
- Sorani Kurdish / RTL interface
- Exchange entries with amount × rate calculation
- Transaction history, search, date filter, delete
- Expense entries
- Daily counts
- JSON backup export and restore
- Local browser storage (no server database)

Important limitations:
- This is a prototype, not audited accounting software.
- No commission/profit, customer balances, cash drawer, staff roles, audit log, or encrypted database yet.
- Data is stored in this browser on this iPhone. Clearing Safari website data can erase it; export backups regularly.
- The app does not upload transaction records to a server.
- Offline PWA installation requires HTTPS hosting. A free option is GitHub Pages; the repository/code can be public, but transaction data remains in the phone's browser storage. Keep backups private.
- To add to iPhone Home Screen: open the deployed HTTPS website in Safari > Share > Add to Home Screen.
