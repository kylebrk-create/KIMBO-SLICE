
# Phil Long Email Kit

This folder is ready to push to **GitHub** and preview via **GitHub Pages**.

## Quick Start
1. Create a repo (e.g. `phillong-email-kit`) and push these files.
2. In repo settings → **Pages** → set *Source* to `Deploy from a branch` → Branch: `main` → `/ (root)`.
3. Open your Pages URL (e.g., `https://<your-username>.github.io/phillong-email-kit/`) and click into `templates/*.html`.

> **Note:** Browsers ≠ email clients. This is a *visual* preview. Outlook uses the Word engine; Gmail has its own quirks. For true email rendering, send tests from your ESP or use Litmus/Email on Acid.

## Interact like a real email
- We included an **`.eml`** file you can open in Apple Mail/Outlook to see it as a message:
  - `eml/accord-hybrid.eml`
- You can also run a local SMTP catch-all (MailHog or Mailpit) and send this HTML via a script (Nodemailer/Python).

## Files
- `index.html` — landing page linking to templates.
- `templates/accord-hybrid.html` — Accord Hybrid promo (600px, dark-mode aware, VML button).
- `eml/accord-hybrid.eml` — Ready-to-open MIME message with the same HTML.

## Next
- Replace placeholder logo URL with your hosted brand asset.
- Swap links for your exact incentive & inventory URLs.
- Add UTM parameters for analytics.
