# OnePage PPT — support site

Support, privacy and terms pages for **OnePage PPT: AI Slide Maker**
(App Store id 6798814385), served via GitHub Pages at
https://alice51849.github.io/onepageppt-support/

- English canonical pages at the root: `index.html`, `support.html`, `privacy.html`, `terms.html`
- The same four pages in all 50 official App Store locales under `<locale>/`
- Generated from `44_OnePagePPT/scripts/generate_store_website.py` content
  (retargeted to this repo); do not hand-edit generated pages.
- Contact: hourstag.app@gmail.com

## Exact-50 support surfaces

The required `index`, `support`, and `privacy` routes are generated or
normalised from `source/support_surfaces.json`:

```bash
python3 tools/support_surfaces.py build
python3 tools/support_surfaces.py check
```

The source records the verified public catalogue and app/privacy authority
digests used for the copy. Do not hand-edit generated locale pages.
