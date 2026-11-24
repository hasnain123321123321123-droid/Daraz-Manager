# E Traders — Daraz Business Manager

## Files
- `index.html`: complete app
- `manifest.webmanifest`: Android install metadata
- `sw.js`: offline cache
- `icon.svg`: app icon

## Important
The app starts with an empty order and payment history, as requested. The five default suppliers are Bada, Ayub, Walayat, Umer and Irshad. Suppliers can be added, renamed or removed. Removing a supplier preserves historical order/payment entries.

Commission is fixed at 38% of the Daraz listed price.
Profit = listed price - 38% commission - supplier cost.
Dashboard profit counts Delivered orders only.
Supplier credit includes costs from all order statuses.
Shipping count includes To Ship and Shipped.
Statuses: To Ship, Shipped, Delivered, Failed Delivery, Return.

## Run / install on Android
For a quick preview, open `index.html` in a browser. For full PWA installation and offline caching, upload the files to an HTTPS static host (for example, a static site hosting service), then open the HTTPS address in Chrome on Android and choose **Install app** / **Add to Home screen**.

## Data safety
Records are saved in the browser's local storage on the device. Use Settings > Download backup regularly. Restore using the JSON backup file. Clearing browser storage or uninstalling/clearing app data can remove local records.
