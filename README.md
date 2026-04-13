# Tashka Healthcare — GitHub Pages Preview Site

Client preview site for **Tashka Healthcare** (tashkahealthcare.com).  
Built by **AdsPilot / FirstDial** · April 2026

---

## 🚀 How to Deploy

```bash
# 1. Clone or download this repo
git clone https://github.com/YOUR_USERNAME/tashka-preview.git
cd tashka-preview

# 2. Push to GitHub (if not already)
git add .
git commit -m "Tashka Healthcare preview site"
git push origin main

# 3. Enable GitHub Pages
# Go to: Settings → Pages → Source: Deploy from branch → main → / (root)
# Site goes live at: https://YOUR_USERNAME.github.io/tashka-preview/
```

No build tools. No npm. No dependencies. Pure HTML — push and it works.

---

## 📁 File Structure

```
tashka-preview/
├── index.html               → Homepage (Healthcare AI Platform)
├── epr-software.html        → EPR Software page
├── clinical-ai.html         → Clinical AI Chat Box page
├── hospital-management.html → Hospital Management Software page
├── contact.html             → Contact & Book a Demo page
├── developer-notes.html     → Developer implementation notes
├── seo-audit.html           → Full SEO audit report
├── img/
│   └── logo/
│       └── tashkatech_logo_web.png
├── qrcode.jpeg
└── README.md
```

---

## 📄 Pages

| Page | File | Primary Keyword | Persona |
|---|---|---|---|
| Homepage | `index.html` | Healthcare AI platform India | All buyers |
| EPR Software | `epr-software.html` | EPR software India | CIO / IT Head / Clinical Lead |
| Clinical AI | `clinical-ai.html` | Clinical AI chatbot hospital | Clinical + Operations |
| Hospital Management | `hospital-management.html` | Hospital management software India | CEO / COO / Finance Head |
| Contact | `contact.html` | Book a demo | All buyers |
| Dev Notes | `developer-notes.html` | — | Developer |
| SEO Audit | `seo-audit.html` | — | Agency / Client |

---

## ⚠️ Before Going to Production

Remove the **yellow dev strip** at the top of every page before pushing to `tashkahealthcare.com`:

1. Delete the `<div class="dev-strip">...</div>` block from all 5 pages
2. Change `nav { top: 41px }` back to `nav { top: 0 }` in all pages
3. Set up 301 redirects on the server:
   - `/custom_ai` → `/clinical-ai`
   - `/hospital_management` → `/hospital-management`
4. Add GA4 tracking code to all pages
5. Create `robots.txt` and `sitemap.xml` at domain root
6. Submit sitemap to Google Search Console
7. Create OG image at `/img/og/tashka-og.jpg` (1200×630px)
8. Replace placeholder reviews with actual GBP review text

Full checklist → see `developer-notes.html`

---

## 🔗 Internal Navigation Map

```
index.html
  ↔ epr-software.html
  ↔ clinical-ai.html
  ↔ hospital-management.html
  ↔ contact.html

All pages → developer-notes.html  (dev strip)
All pages → seo-audit.html        (dev strip)
developer-notes.html → seo-audit.html
seo-audit.html → developer-notes.html
```

---

## ✅ What's Implemented

**SEO**
- Unique `<title>` tags on all pages (keyword-optimized)
- Unique meta descriptions on all pages (150–160 chars)
- `<link rel="canonical">` on all pages
- Open Graph + Twitter card tags on all pages
- JSON-LD structured data: Organization, LocalBusiness, SoftwareApplication, FAQPage
- Schema.org Review microdata on all review cards
- Correct H1 hierarchy — one H1 per page, primary keyword included
- Internal contextual links between all pages
- Hyphenated URL slugs (SEO best practice)

**Design & UX**
- Design system matched exactly to existing tashkahealthcare.com
- Font: Inter | Colors: #2563eb blue, #1fb981 WhatsApp green
- Sticky CTA bar — appears after hero scroll, hides near final CTA
- Mobile hamburger menu with drawer — fully functional
- Responsive at 968px, 640px, 400px breakpoints
- Google Reviews section on all pages (5 cards + GBP link)
- Footer: Quick CTA (Demo + WhatsApp) replacing the low-converting form

**Pages**
- EPR Software and Hospital Management are intentionally differentiated:
  - EPR → clinical/technical angle, targets CIO/IT persona
  - Hospital Management → operational angle, targets CEO/COO/Finance persona
  - Zero "EPR" terminology in Hospital Management body content

---

## 📞 Contact

**AdsPilot / FirstDial**  
Prepared for: Tashka Healthcare · tashkahealthcare.com  
April 2026
