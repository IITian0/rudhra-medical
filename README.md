# Rudhra Medical — Online Pharmacy Website

A single-page, self-contained pharmacy website for **Rudhra Medical** with a
3-tap ordering flow and an **English / Hindi** language switch.

## Live site
After enabling GitHub Pages (Settings -> Pages -> Branch: `main` / root), the site is served from `index.html`.

## Features
- **3-tap ordering** — find, add, send order on WhatsApp.
- **English / Hindi toggle** (EN / हिं) — the whole site, products and the WhatsApp order message switch language.
- **Symptom quick-picks** — "Fever", "Cough & Cold", etc. drop a ready combo into the cart.
- **One-tap reorder** of the previous order.
- **Prescription photo -> WhatsApp** flow.
- **Voice search** (browser supported).
- **Cart saved in the browser** (localStorage) and **one-tap WhatsApp checkout**.
- **Medical-only palette**: pharmacy green, clinical blue, white, and red only for Rx tags.

## Customise
1. Open `index.html`.
2. Set your WhatsApp number in `const PHONE = "91XXXXXXXXXX";` (country code, no `+`).
3. Edit the `PRODUCTS` array for your real product list and prices.
4. Replace the footer placeholders (address, drug licence, GSTIN).

## Files
- `index.html` — the website.
- `invoice/Rudhra_Medical_Invoice_Template.xlsx` — GST tax-invoice template + product list sheet.

---
*Sample website built for Rudhra Medical. Replace the placeholder details with your real ones.*
