FIVE STAR AGENCIES — WEBSITE FILES
====================================

WHAT'S INSIDE
  index.html      Homepage
  products.html   Catalogue (Electronics / Furniture / Vessels)
  about.html      About page
  contact.html    Contact page with a working form (Netlify Forms)
  privacy.html    Privacy Policy — use this URL for Meta/WhatsApp API
  terms.html      Terms of Service
  style.css       Shared styling for all pages

BEFORE YOU PUBLISH — replace these placeholders in ALL files:
  1. Phone number: 910000000000
     Find/replace with your real WhatsApp Business number, in international
     format with no + or spaces (e.g. 919876543210 for a +91 number).
     It appears in: index.html, products.html, contact.html.

  2. Email: contact@fivestaragencies.shop
     Replace with your real support email.
     It appears in: index.html, privacy.html, terms.html, contact.html.

  3. Address: "Add your business address here"
     In contact.html and, if your country requires it, privacy.html.

HOW TO DEPLOY (Netlify — free)
  1. Go to netlify.com and sign up / log in.
  2. From your dashboard, drag this whole folder onto the deploy area
     (or use "Add new site" → "Deploy manually").
  3. Netlify gives you a temporary URL like random-name.netlify.app —
     check the site works there first.
  4. Go to Site settings → Domain management → Add a domain →
     enter fivestaragencies.shop
  5. Netlify shows you DNS records. Go to wherever you bought the domain
     (GoDaddy, Hostinger, Namecheap, etc.) → DNS settings → add those
     records exactly as shown.
  6. Wait for DNS to propagate (minutes to ~24 hours). Netlify will
     auto-issue a free SSL certificate once it verifies the domain.
  7. Once https://fivestaragencies.shop/privacy.html loads with the
     padlock icon, use that exact URL as your Meta / WhatsApp Business
     API Privacy Policy URL.

CONTACT FORM
  The form on contact.html uses Netlify Forms — no backend needed.
  Once deployed on Netlify, submissions will appear under
  Site settings → Forms in your Netlify dashboard automatically.
  This does NOT work if you host the files anywhere other than Netlify
  (e.g. GitHub Pages, Vercel) without swapping in a different form
  handler.

PRODUCT LISTINGS
  The items in products.html are placeholder examples with sample
  prices — edit the names, descriptions, and prices to match what you
  actually sell. Each "Enquire" link opens WhatsApp with a pre-filled
  message naming that product.
