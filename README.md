# World Islands Database
Sortable list of every island in the world. Deployed to islands.cadenharvey.biz on Cloudflare Workers; auto-deploys on every push to `main`.

The page is `index.html`; the data lives in `data/` (islands over 1 km² in `islands.json`, smaller ones in `small_1..3.json`), so the data can be updated without touching the page.
