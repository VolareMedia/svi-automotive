# SVI Automotive Equipment — Website

Static marketing site for **SVI Automotive Equipment** (Victoria, BC) — Vancouver Island's
trusted source for automotive shop equipment and an authorized **Atlas Automotive Equipment** dealer.

No build step. Plain HTML + CSS.

## Pages
- `index.html` — homepage
- `vehicle-lifts.html` — vehicle lifts
- `tire-changers.html` — tire changers
- `wheel-balancers.html` — wheel balancers
- `service.html` — service & repair
- `contact.html` — contact + financing
- `styles.css` — shared styles
- `assets/` — SVI logo images

## Local preview
```bash
python3 -m http.server 8000
```
Then open http://localhost:8000

## Before public launch (in progress)
- [ ] Mobile responsiveness — no media queries yet; layout is desktop-first
- [ ] Wire up the contact form (currently `action="#"`) to a form service (e.g. Formspree)
- [ ] Host product/hero images locally (several are hotlinked from manufacturer CDNs)
- [ ] Confirm social links, email, and full product lineup with Bruce
- [ ] Add favicon + social share (Open Graph) image
