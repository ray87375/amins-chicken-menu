# Amin's Chicken menu

The digital menu behind the QR code on Amin's Chicken takeaway bags (Batroun, Lebanon).
English and Arabic, built for phones. One static file, no build step.

## Edit the menu

Open `index.html` and find `EDIT THE MENU HERE`. Each dish has:

- `name` and `desc` in `en` and `ar`
- `price` in Lebanese pounds (L.L), or `null` to show "–"
- `tag: "popular"` or `"veg"` (optional)

The poster strip under the header is the `POSTERS` list further down in `index.html`.
Add a poster by adding one entry with its image (a 380 × 475 px JPEG, as a base64 data URI) and the menu section it jumps to.

## Hosting

Deployed on Vercel from this repo. Every push to `main` updates the live menu,
so the QR code never needs reprinting.
