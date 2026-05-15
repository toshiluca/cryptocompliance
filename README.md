# cryptocompliance.io

Static one-page website for CryptoCompliance, LLC. No build step — plain HTML, CSS, and JS.

## Files

- `index.html` — page structure and content
- `styles.css` — all styling
- `script.js` — nav toggle, FAQ accordions, form submission
- `assets/` — images and logos

## Local preview

Open `index.html` in a browser, or from this folder run:

```
python3 -m http.server 8000
```

Then visit <http://localhost:8000>.

## Contact form

The form submits to [Formspree](https://formspree.io). The `action` attribute in `index.html` must be replaced with the Formspree endpoint URL (currently shows `REPLACE_WITH_YOUR_FORMSPREE_ID` placeholder) before deployment.

## Deployment

Hosted on Cloudflare Pages, pulling from this repository.
