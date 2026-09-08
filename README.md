# backpackofsongs.com

The published output of the Backpack of Songs marketing site. This repo holds
only the generated static files — it is not where the site is edited.

The source lives in the app's own repo, at `site/`. To make a change:

1. Edit `site/_template.html` (and/or `docs/legal/*.md` for the legal pages).
2. Run `python3 site/build.py`.
3. Copy the files it produces (`index.html`, `press.html`, `terms.html`,
   `privacy.html`, `guidelines.html`, `delete-account.html`, `backpack.svg`)
   into this repo, replacing what is here — along with the artwork the pages
   load beside themselves: `manhattan.jpg`, `avatar.png`, `shot-radar.jpg`,
   `shot-card.jpg`, `hero-scene.jpg`, `og-card.jpg`, `app-icon-1024.png` and
   the four favicon files.
4. Commit and push — GitHub Pages redeploys automatically.

Served via GitHub Pages with the custom domain `backpackofsongs.com`
(see the `CNAME` file). DNS is managed at GoDaddy; see the app repo's
`site/README.md` for the record values.
