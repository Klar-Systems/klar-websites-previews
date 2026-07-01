# klar-websites-previews

Gallery of generated restaurant website previews — the delivery output of the Klar
lead pipeline (`klar-pipeline`).

Each subfolder is one prospect's preview site (283 and counting, e.g.
`alanya-pizzeria/`, `annanpippuri/`, `blueberry-coffee/`), sent to restaurants as a
live demo of the site Klar can build for them.

## Hosting
Served via GitHub Pages on the custom domain in `CNAME` → **preview.klarsystems.com**.
A prospect's preview lives at `preview.klarsystems.com/<restaurant-slug>/`.

## Structure
- `<restaurant-slug>/` — one generated preview site per lead
- `CNAME` — custom domain for GitHub Pages

## Related repos
- `klar-pipeline` — generates these previews (lead research → site build → deploy)
- `Klar-website` — main marketing site + formal client proposals
