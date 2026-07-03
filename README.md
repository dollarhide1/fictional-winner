# Nursing Career Pathways & Action Plan — Landing Page

The marketing landing page for **Nursing Career Pathways & Action Plan**, an
interactive career planner for nurses. Visitors explore the page and click
through to the Payhip checkout to buy the app.

**Live checkout:** https://payhip.com/b/nvo4P

## What's in this repo

| File | Purpose |
| --- | --- |
| `index.html` | The entire landing page — self-contained (inline CSS, inline SVG, Google Fonts via CDN). This is the site. |
| `favicon.ico` | Browser-tab icon (the lavender cross mark). |
| `apple-touch-icon.png` | Home-screen icon for iOS/iPadOS. |
| `README.md` | This file. |

That's the whole site. `index.html` references no local images, stylesheets,
or scripts, so nothing else is required.

## Deploying

Any static host works, because the site is a single HTML file.

**Netlify** — drag the folder onto the Netlify dashboard, or connect this
repo and deploy. No build command and no publish directory settings are
needed.

**GitHub Pages** — in the repo, go to *Settings → Pages*, choose the `main`
branch and the root (`/`) folder, and save. Your page publishes at
`https://<username>.github.io/<repo>/`.

A file named `index.html` at the repo root is served as the homepage
automatically. `favicon.ico` and `apple-touch-icon.png` at the root are
picked up by browsers with no extra setup.

## Updating the checkout link

Every "Get instant access" button points to the Payhip product URL. If that
link ever changes, open `index.html` and replace each occurrence of
`https://payhip.com/b/nvo4P` (there are four).

## Not in this repo (on purpose)

The **paid product** is delivered through Payhip, not from here. The app file
and the downloadable `.zip` are intentionally kept out of this public repo so
they can't be downloaded for free. Only the landing page lives here.

---

*Educational planning tool. Not affiliated with any nursing board, school, or
certifying body. Requirements vary by state and program — always verify with
your state board of nursing and each accredited program.*
