# Setiawalk Parking Claim Scanner (Bimage Consulting)

A lightweight, 100% client-side web app that scans Touch 'n Go `Customer Transactions Statement` PDFs for `SM_A01` Setiawalk Parking entries, crops each row screenshot automatically, calculates the total parking `RM` amount, and exports both `.docx` (using your exact Bimage Consulting Word template) and `.pdf`.

## How to Use Locally (Zero Install)
1. Double-click `index.html` to open it in Microsoft Edge or Google Chrome.
2. Drag and drop your Touch 'n Go statement PDF (e.g. `Statement (6).pdf`).
3. Review the auto-detected Employee Name, Claim Month, cropped `SM_A01` rows, and live `RM` total.
4. Click **Download Word (.docx)** or **Download PDF (.pdf)**.

## How to Share with Colleagues for Free (RM 0 — No Domain Needed)
- **Option 1 (Share file directly):** Send `index.html` via Microsoft Teams, WhatsApp, Email, or place it in a shared OneDrive/SharePoint folder. Because the Bimage Word template is embedded inside `index.html`, colleagues just double-click it to run.
- **Option 2 (Free web link via Netlify Drop / Cloudflare Pages / GitHub Pages):**
  - Go to https://app.netlify.com/drop (or Cloudflare Pages) and drag-and-drop this `parking-claim-app` folder.
  - You will get a free `https://...` link immediately with zero hosting or domain fees. All PDF processing stays 100% local inside each user's browser.
