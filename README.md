# E4RTH R4DIO support site

Static pages for App Store Connect:

- `index.html` is the **Support URL**
- `privacy.html` is the **Privacy Policy URL**
- `terms.html` is the optional Terms of Use / EULA URL

Before publishing, search all three files for `class="ph"` and replace the yellow placeholders
(name, contact email, postal address, state or country). `index.html` and `privacy.html`
need the email; `terms.html` needs everything.

## Publish on GitHub Pages
1. New public repo, e.g. `r4dio-support`; upload these files to the root.
2. Settings, Pages, Source: *Deploy from a branch*, `main`, `/ (root)`, Save.
3. Your URLs: `https://<username>.github.io/r4dio-support/` (support), `.../privacy.html`, `.../terms.html`.
