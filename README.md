# DueThread website

Home, about, Pro, support, privacy and terms pages for the DueThread Chrome extension, published with GitHub Pages.

- `index.html`: home page
- `about.html`: why DueThread exists, in Prem's words
- `pro.html`: DueThread Pro, plans and the buy button
- `thanks.html`: the page buyers return to after paying; shows their licence key
- `support.html`: help and contact
- `privacy.html`: privacy policy (linked from the Chrome Web Store listing)
- `terms.html`: terms of use and sale, including refunds
- `404.html`: page-not-found

The Chrome Web Store link is already filled in on every page. The one address to set is the licence service in `thanks.html` (the `licence-api` meta tag, line 9).

## Editing on Windows

Every file is plain ASCII: special characters are written as HTML entities, such as `&copy;` for the copyright sign and `&mdash;` for a long dash. Keep it that way. Windows PowerShell's `Get-Content` and `Set-Content` read and write files in the Windows code page, which turns characters such as the copyright sign and the long dash into two or three stray symbols each. To edit a page, use Notepad or VS Code, and type special characters as entities.
