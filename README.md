# DueThread website

Home page, privacy policy and support pages for the DueThread Chrome extension, published with GitHub Pages.

- `index.html`: home page
- `privacy.html`: privacy policy (linked from the Chrome Web Store listing)
- `support.html`: help and contact
- `pro.html`: DueThread Pro, plans and the buy button
- `thanks.html`: the page buyers return to after paying; shows their licence key
- `terms.html`: terms of use and sale, including refunds
- `404.html`: page-not-found

The support email appears in `privacy.html`, `support.html` and `pro.html`. When the store listing is live, replace the "coming soon" line in `index.html` with a link to it.

`thanks.html` needs the licence worker's address in its `licence-api` meta tag (replace `LICENCE_API_URL`).

Before publishing, two addresses must be filled in: `STORE_URL` (the Chrome Web Store listing, in several pages) and `LICENCE_API_URL` (the licence worker, in thanks.html).
