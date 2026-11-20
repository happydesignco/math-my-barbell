# Math My Barbell

Barbell plate calculator. Enter any reference weight — your 1RM, training max,
top set, whatever — and see the loaded bar for every percentage from 100% down
to 25%.

Single self-contained `index.html` file — no build step, no dependencies.

## Features

- Lb and kg, with conversion when you toggle units
- Bar selection (lb: 45/35/15 plus a 65 lb trap bar, kg: 20/15/10)
- Custom plate inventory — toggle off plates you don't have
- Round mode: nearest / up / down
- Tap a row to see the loaded bar diagram
- Shareable URLs (`?w=225&bar=45&u=lb`) — coaches can link directly to a working weight
- Remembers your last setup via localStorage
- Mobile-first, dark/light follows system

## Run locally

```sh
# any static server works
python3 -m http.server 8000
# then open http://localhost:8000
```

Or just double-click `index.html`.

## Deploy

It's a single file plus a manifest. Drop on any static host:

- GitHub Pages: push to a repo, enable Pages on `main` / root
- Cloudflare Pages / Netlify / Vercel: connect repo, no build command, output `.`
- Sevalla: same — static site, root directory

## Feedback

[adam@happydesigncompany.com](mailto:adam@happydesigncompany.com)
