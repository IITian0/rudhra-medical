# Shree Rudra Medical Agencies — Online Pharmacy Website

A single-page, self-contained pharmacy website for **Shree Rudra Medical Agencies**
with a clean, Tata 1mg-style layout and an **English / Hindi** language switch.

## Live site
GitHub Pages serves this from `index.html` (Settings -> Pages -> Branch: `main` / root).

## What's on the page
- Header with logo, nav tabs (Medicines, Lab Tests, Consult Doctors, Health Concerns, Ayurveda, Offers) and cart.
- City selector + big product search, plus a "Quick buy" block.
- "Order with prescription" hero banner and an upload card.
- **Shop by health concerns** (9 categories with icons).
- **Full body health checkups** cards with SAFE badge and discounts.
- **Featured products** grid with ratings, price, MRP, % off and "Get by Today".
- **Popular categories** grid.
- **Order medicines on call** section.
- Footer with licence/GSTIN and contact.

## Features
- **English / Hindi toggle** (EN / हिं) — whole site and WhatsApp messages switch language.
- **One-tap WhatsApp checkout** — the cart (items + total) goes to **+91 89577 85613**.
- **Prescription upload -> WhatsApp**, health-checkup booking and call-back request all open WhatsApp.
- Cart saved in the browser (localStorage).
- Medical-only palette: pharmacy green, white, and red for SAFE/Rx badges.

## Customise
1. Open `index.html`.
2. Change the WhatsApp number in `const PHONE = "918957785613";`.
3. Edit the `PRODUCTS`, `CHECKUPS`, `CONCERNS` and `CATS` arrays for your real data.
4. Replace the footer placeholders (address, drug licence, GSTIN).

## Files
- `index.html` — the website.
- `invoice/Rudhra_Medical_Invoice_Template.xlsx` — GST tax-invoice template + product list sheet.

---
*Sample website built for Shree Rudra Medical Agencies. Replace the placeholder details with your real ones.*
