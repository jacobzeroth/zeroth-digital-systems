# Zeroth Digital Systems

Marketing site and working demos for Zeroth Digital Systems — practical dashboards, inventory and factory operations systems for small manufacturers.

Static HTML, CSS and JavaScript. No build step, no dependencies, no tracking.

## Live

- https://zeroth.pages.dev — Cloudflare Pages (primary)
- https://jacobzeroth.github.io/zeroth-digital-systems/ — GitHub Pages (mirror)

## Structure

```
.
├── index.html                   Marketing site
├── zeroth-inventory-lite.html   Inventory demo
├── zeroth-factory-ops.html      Factory operations demo
├── zeroth-brochure.pdf          Two-page brochure
├── assets/                      Screenshots used by the site
├── docs/                        Launch kit and operating notes
└── source/                      Working files (brochure HTML, certificate maker, full-size screenshots)
```

## Preview locally

```bash
python -m http.server 8099
```

Then open <http://127.0.0.1:8099/>.

The pages also work when opened directly from disk, but a local server matches how they behave when hosted.

## Demos

Both demos are self-contained and store their changes in `localStorage`. They never send data anywhere. The data is fictional and labelled as such. Use **Reset data** in the demo top bar to restore the original sample.

## Contact

- WhatsApp: [+91 91768 95044](https://wa.me/919176895044)
- Email: [founderofzeroth@gmail.com](mailto:founderofzeroth@gmail.com)
- Location: Kallakurichi, Tamil Nadu — remote delivery across India

## Notes

- Prices are introductory pilot prices and are confirmed in writing before payment.
- The brochure PDF is generated from `source/zeroth-brochure.html`.
- Screenshots in `assets/` are captures of the real demos with fictional data.
