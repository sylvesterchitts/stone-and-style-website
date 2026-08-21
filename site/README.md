# Stone & Style Solutions — Website

A single-page website for Stone & Style Solutions (Harare), built with the brand logo and palette.

## What's in the folder

```
index.html            The whole website (HTML + CSS + JS in one file)
assets/img/           Logo files and photography
README.md             This file
```

## How to put it online

**Option 1 — drag and drop (easiest, free)**
1. Go to https://app.netlify.com/drop
2. Drag the whole `site` folder onto the page.
3. You get a live link straight away. Add your own domain later in Netlify's settings.

Cloudflare Pages and Vercel work the same way.

**Option 2 — normal web hosting (cPanel / FTP)**
Upload the contents of this folder into `public_html`. `index.html` must sit at the top level so it loads as the homepage.

Nothing needs to be installed or compiled — it's plain HTML.

## Brand colours used

| Colour | Hex | Where |
|---|---|---|
| Navy | `#003756` | Buttons, headings, contact band |
| Deep navy | `#00243a` | Hero, process section, footer |
| Grey | `#686a6c` | Body text accents |
| Tan | `#967357` | Eyebrow labels, accents |
| Light tan | `#aa8c77` | Hero highlight text |
| Dark brown | `#64401e` | Mosaic accents |
| Olive | `#807e5c` | List bullets, tick icons |

Fonts: **Poppins** (headings) and **Inter** (body), loaded from Google Fonts.

## Things you may want to change

**Phone / WhatsApp number** — search `263785107913` in `index.html` and replace everywhere (it appears in the header, hero, contact section, footer and the floating green button).

**Address** — search `Telford Road`.

**Opening hours** — in the "Opening times" block inside the contact section, and once more in the footer.

**Prices** — the aluminium glass door price `$100` appears twice: in the services card and on the badge over the wardrobe photo. Countertops are deliberately quoted per project. If you run the `$95` promotion again, the cleanest place to add it is a banner just above the `<header>`.

**Photos** — replace files in `assets/img/` keeping the same file names, and the site updates automatically. Landscape shots work best at about 1400px wide; the hero image is portrait.

**Adding a contact form** — the site currently sends people to WhatsApp, which needs no backend. If you later want a form, Formspree or Netlify Forms will drop into the contact section without any other changes.

## Notes

- Works on phones, tablets and desktop.
- Gallery images open larger when tapped.
- Page title and description are already written for Google; update them in the `<head>` if the service list changes.
