# For Little Hearts Fund — Website

Website of the For Little Hearts Fund (Vietnamese: *Quỹ “Vì những trái tim bé bỏng”*), QN, Vietnam, established under Decision No. 315/UBND.

## Structure
- `index.html` — home page
- `gioi-thieu.html` — About
- `chuong-trinh.html` — Programme
- `hoat-dong.html` — Activities
- `minh-bach.html` — Transparency
- `lien-he.html` — Contact
- `404.html` — custom 404 page (GitHub Pages uses it automatically when a page is not found)
- `robots.txt`, `sitemap.xml` — help Google index the site and support Google Ad Grants
- `css/style.css` — all styles
- `js/main.js` — mobile menu (closes on outside click / Esc) + current year in the footer

File names are kept unchanged so existing links, the sitemap and any ads keep working.

## Features
- `canonical`, Open Graph and Twitter Card tags on every page (social sharing and SEO)
- `aria-current="page"` + active menu state so visitors know which page they are on
- `robots.txt` + `sitemap.xml` listing all 6 pages
- Custom 404 page
- Mobile menu closes on outside click or the Esc key
- Contact form on the Contact page, sending real email through FormSubmit.co (free, no account needed — just confirm the email once when the first message arrives)
- Google Analytics (GA4) snippet on every page — replace `G-XXXXXXXXXX` with the real Measurement ID to activate
- `docs/google-ad-grants.md` — reference content for the Google Ad Grants application (mission statement, campaign themes, sample ads, checklist)

## Run locally
Open `index.html` in a browser, or use any static server, for example:

```
python3 -m http.server 8080
```

## Deploy with GitHub Pages
Go to **Settings → Pages** in this repository, choose branch `main`, folder `/ (root)`, then Save. After a few minutes the site runs at:

```
https://hvhwan-debug.github.io/TTBB/
```

## Still to update
- Confirm the correct contact phone number (currently: +84 913 498 459)
- Real logo and photos of activities (illustrations are used for now)
