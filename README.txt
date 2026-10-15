FAZAL E RABBI TRADDERS - OFFLINE WEB APP (FIRST VERSION)

This is a PWA: a website that can be added to an iPhone Home Screen and, after successful first load, can run offline.

IMPORTANT: Opening index.html directly as a file is NOT sufficient for iPhone Home Screen offline installation. Upload the entire folder contents to an HTTPS static host (e.g., GitHub Pages / Netlify). All files must remain together.

iPhone: Open its HTTPS URL in Safari while online > Share > Add to Home Screen > Add. Launch once while online and then test in Airplane Mode.

Data is stored only in this browser's localStorage, not synced. Export JSON backups regularly using Reports > Export JSON Backup, and keep files private. Clearing Safari website data/removing the app can delete records. Backups are NOT encrypted. No PIN/biometrics in this version. Offline mode must be verified on the actual device.

Features: stock/batches and expiry, sales with customer credit, customers/suppliers, payments, purchases, expenses, daily and monthly profit reports, JSON import/export.

This is an initial prototype. Test calculations and backup/restore with sample records before using for real shop accounting.

PHASE 3A (2026-10-15): Edit product metadata/prices (not historical prices), customer/supplier details, expenses, and payment amounts. A corrections audit list is shown in Reports. Existing storage KEY remains unchanged. Do not edit sale/purchase transactions via this build; use returns and fresh corrected transactions until transaction-safe editing is implemented. Always export and keep a verified backup before upgrading.
