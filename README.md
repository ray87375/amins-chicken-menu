# Amin's Chicken menu

The digital menu behind the QR code on Amin's Chicken takeaway bags (Batroun, Lebanon).
English and Arabic, built for phones. One static file, no build step.

## Edit the menu

Open `index.html` and find `EDIT THE MENU HERE`. Each dish has:

- `name` and `desc` in `en` and `ar`
- `price` in USD, or `null` to show "–"
- `tag: "popular"` (optional)
- `img: "photos/whole-farrouj.jpg"` (optional) to replace the placeholder tile

Put photos in a `photos/` folder. Square crops around 300×300 px work best.

## Hosting

Deployed on Vercel from this repo. Every push to `main` updates the live menu,
so the QR code never needs reprinting.
