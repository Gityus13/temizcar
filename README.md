# 💧 TemizCar.az

**Azerbaijan's #1 Self-Service Car Wash** — [temizcar.az](https://temizcar.az)

A fully static, single-page website for TemizCar, hosted on GitHub Pages.

---

## 🚀 Live Site

**[https://temizcar.az](https://temizcar.az)**

---

## 📁 File Structure

```
/
├── index.html        # Main website (single-page)
├── privacy.html      # Privacy Policy page (AZ / RU / EN)
├── robots.txt        # Search engine crawl rules
├── sitemap.xml       # Sitemap for SEO
├── CNAME             # Custom domain: temizcar.az
└── README.md         # This file
```

---

## ✨ Features

- 🌍 **7 languages** — Azerbaijani, Russian, English, Turkish, German, French, Arabic (with RTL support)
- 🚗 **Scroll-animated car wash** — GSAP-powered interactive car cleaning animation
- 💬 **Contact form** — Powered by [FormSubmit.co](https://formsubmit.co), sends to `yusif.kurba@gmail.com`
- 📍 **Locations** — Quba (open) and Baku (coming soon) with Google Maps embed
- ⭐ **Testimonials** — Auto-scrolling marquee, localised per language
- ❓ **FAQ** — Accordion, localised per language
- 🍪 **Cookie banner** — With localStorage persistence
- 🔍 **SEO-ready** — `og:image`, canonical tag, `LocalBusiness` JSON-LD schema, `robots.txt`, `sitemap.xml`
- 📱 **Fully responsive** — Mobile-first, hamburger nav, no external CSS frameworks
- ⚡ **Active nav highlight** — Scroll spy highlights current section
- 🎨 **Custom cursor** — Desktop only, with hover effect

---

## 🛠 GitHub Pages Setup

1. Go to **Settings → Pages** in this repository
2. Set **Source** to `Deploy from a branch`
3. Select **branch:** `main` (or `master`), **folder:** `/ (root)`
4. Click **Save**
5. Your site will be live at `https://<your-username>.github.io/<repo-name>/`

### Custom Domain (CNAME)

The `CNAME` file already contains `temizcar.az`. In your DNS provider:

| Type | Name | Value |
|------|------|-------|
| A | @ | 185.199.108.153 |
| A | @ | 185.199.109.153 |
| A | @ | 185.199.110.153 |
| A | @ | 185.199.111.153 |
| CNAME | www | `<your-username>.github.io` |

---

## 📧 Contact Form (FormSubmit.co)

The contact form posts to `https://formsubmit.co/yusif.kurba@gmail.com`.

**First submission:** FormSubmit will send a confirmation email — you must click the activation link once to start receiving form submissions.

**Configuration** (set in hidden fields inside the form):
- `_subject` — Email subject line
- `_captcha` — Set to `false` (no CAPTCHA)
- `_template` — Set to `table` for clean formatting

---

## 🔄 Updating Content

| What | Where |
|------|-------|
| Phone numbers | Search for `+994507069438` in `index.html` |
| Baku location details | Search for `baku_addr` in the JS translations object |
| Prices | Search for `plan-price` section in `index.html` |
| Testimonials | `TESTIMONIALS` object in JS |
| FAQ | `FAQ_DATA` object in JS |
| Social links | Search for `facebook.com/temizcar.az` in `index.html` |
| Google Maps embed | Search for `locations-map-full` in `index.html` |

---

## 📞 Contacts

- **Farid Qurbanov** (Quba Branch) — +994 50 706 9438
- **Nizami Cavadov** (Technical) — +994 99 549 9933
- **Email** — info@temizcar.az

---

*© 2026 TemizCar Azerbaijan. All rights reserved.*
