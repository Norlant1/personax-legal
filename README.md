# Persona X — Legal pages

Static site hosted on GitHub Pages serving the Privacy Policy and Terms of Service for the [Persona X](https://github.com/Norlant1/first-steps-folder) mobile app.

## Live URLs

- Landing: https://norlant1.github.io/personax-legal/
- Privacy Policy: https://norlant1.github.io/personax-legal/privacy/
- Terms of Service: https://norlant1.github.io/personax-legal/terms/

## Editing

Two source-of-truth markdown files are kept at the repo root for easier editing/diffing:

- `privacy-policy.md`
- `terms-of-service.md`

The HTML files in `privacy/` and `terms/` are what GitHub Pages actually serves. **When you change a markdown file, you must also update the matching HTML file.** If that becomes a hassle, switch to a Jekyll/Eleventy build later.

The `.nojekyll` file disables Jekyll processing so the markdown files aren't auto-served at conflicting URLs.

## Updating the "Last updated" date

When you make a material change to either document, update the `Last updated:` date at the top of:

1. The `.md` source file
2. The corresponding `index.html` page

…and notify users in-app or by email if the change is material.
