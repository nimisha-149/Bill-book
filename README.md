# Bill Book – Project 7

A simple offline-first billing web app.

## Features
- Shop profile and customer details
- Add items with quantity and discount
- Automatic tax and total calculation
- Bill history stored in the browser
- Daily sales total
- Print / Save as PDF
- Share bill text
- UPI payment deep link
- PWA manifest and service worker for offline use

## Run
Open `index.html` in a modern browser. For best PWA installation, host the folder using a simple local web server or deploy it to a static hosting service.

## Important note
The UPI button creates a real UPI payment link for the exact bill total. A production Android app can use a native QR-code generator to render this link as a fully scannable QR code.
