# CE Course Feedback page

**Current version:** v1.2 (Nov 6, 2026)

## What this is
Landing page for the Yanke Bionics continuing-education feedback QR stickers.
QR sticker on course packet -> this page -> anonymous Microsoft Form.

## Files
- `index.html` - the landing page (single file, logo inlined, no outside requests)
- `.nojekyll` - tells GitHub Pages to serve files as-is

## Locked decisions
- Feedback only, fully anonymous. No names, emails, or sign-in.
- Responses live in the Microsoft Form inside Yanke's Microsoft 365.
- The QR points at THIS page, not the form, so printed stickers keep working if the form is ever replaced. To swap forms, change the button link in index.html only.
- No CE-credit or accreditation claims on the page or sticker.
- Page is set to noindex so it does not show up in search results.

## Shipped
- v1.2 (Nov 6, 2026): live form link added, version stamp in footer.

## Open
- Generate QR + print-ready sticker art once the Pages URL is live.
- Sticker print run pending leadership approval.
