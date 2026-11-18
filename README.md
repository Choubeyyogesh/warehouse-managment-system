# WarehousePro

A responsive, frontend-only warehouse inventory demo built with HTML, CSS, and vanilla JavaScript. It uses browser `localStorage`; no server or database is required. Open `index.html` through a local static server (ES modules require HTTP in some browsers), for example VS Code Live Server.

## Modules

- `index.html` — semantic app shell and navigation.
- `css/styles.css` — theme, responsive layout, tables, forms, and dark mode.
- `js/data.js` — clearly editable sample data.
- `js/store.js` — state, persistence, and data mutations.
- `js/views.js` — dashboard, lists, stock status, and reports.
- `js/forms.js` — module forms and CSV export.
- `js/app.js` — routing, event handling, and page rendering.

## Features

Dashboard metrics, product CRUD, stock adjustment and alerts, incoming/outgoing shipment records, warehouse locations, search, inventory valuation, CSV export, responsive mobile navigation, and dark mode. Data stays in this browser. Login/register is not included because the brief describes simulated authentication as optional and the demo is frontend-only.

To reset demo data, clear the browser's site storage for the local app (key `warehousepro-data-v1`).
