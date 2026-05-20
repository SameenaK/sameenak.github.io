# Sameena Khan — Portfolio Site

Static personal portfolio. Two case studies plus a home page.

## Stack

- Static HTML / CSS / JS — single file per page, no build step
- Hosted on GitHub Pages at [sameenak.github.io](https://sameenak.github.io)
- Contact form posts to Formspree (form ID stored in `index.html`)

## File Structure

```
index.html           home page (hero, about, work, voices, career, contact)
aap-detail.html      case study: AAP Search Experience
cpi-detail.html      case study: CPI Event Registration Experience
images/              image assets, referenced as `images/<filename>`
```

Each HTML file is self-contained — `<style>` blocks live inline, no external CSS.

## Local Development

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

Or right-click `index.html` in VS Code → **Open with Live Server**.

## Deployment

```bash
git add .
git commit -m "Description of change"
git push
```

GitHub Pages rebuilds within ~1 minute.

## Design Notes

- **Type:** Public Sans for prose, JetBrains Mono for labels / dates / tag pills
- **Accent color:** plum (`#7C3AED`), used for UI elements only — never prose
- **Layout:** container max-width 1100px, prose column 720px, mobile breakpoint 768px
- **No italics, no phone-frame mockups, no browser-chrome mockups** — editorial tone, image content is the focal point
