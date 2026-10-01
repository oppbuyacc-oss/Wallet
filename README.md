# Wallet

A polished browser build inspired by the uploaded Apple Wallet / American Express screenshots.

## Run
Open `index.html` directly in a browser, or serve the folder with any static HTTP server.

## Included interactions
- Wallet-style home screen with the uploaded `amexbusinnes.jpg` as the main card.
- Locked card with Face ID unlock sheet.
- Unlock/lock states persisted in localStorage.
- Card details and verification sheets.
- Activity/transaction list with saved entries.
- Payment flow: unlock → hold near reader → simulated reader verification → success receipt.
- Synthesized Apple Pay-style confirmation tone (not Apple's original audio).
- Settings for Face ID state and sound.

## Safety / platform limits
This is a UI prototype. It does not perform real financial transactions, store payment credentials, contact American Express, or access the device's Face ID hardware. Browser-based NFC/payment hardware access is not used; the reader interaction is simulated.
