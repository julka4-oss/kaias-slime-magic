# Kaia's Slime Magic

The website for Kaia's handmade slime shop. It's a plain static site hosted on GitHub Pages.

- `index.html` is the whole shop page: products, about, safety, shipping, FAQ, terms and privacy.
- `thank-you.html` is where Stripe sends buyers after they pay.
- `logo.png` is the current logo.

## Changing the slimes

Edit the `SLIMES` list near the bottom of `index.html`. Each slime has a name, texture, scent, price, size, description, two colors and optional `photo` and `link` fields:

- `link`: paste the slime's Stripe Payment Link. With no link the button says "Coming soon".
- `soldOut: true` shows "Sold out".
- `photo`: path to a photo in this repo (for example `photos/blue-raspberry.jpg`).
