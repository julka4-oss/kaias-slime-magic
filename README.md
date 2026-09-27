# Kaia's Slime Magic

The website for Kaia's handmade slime shop. It's a plain static site hosted on GitHub Pages.

- `index.html` is the whole shop page: products, about, safety, shipping, FAQ, terms and privacy.
- `thank-you.html` is where Stripe sends buyers after they pay.
- `logo.png` is the current logo.

## Changing the slimes

Edit the `SLIMES` list near the bottom of `index.html`. Each slime has a name, texture, scent, price, size, description, two colors and an optional `photo`:

- `soldOut: true` shows "Sold out".
- `photo`: path to a photo in this repo (for example `photos/blue-raspberry.jpg`).

## The slime jar (cart)

The jar button next to Shop is the cart. It remembers slimes in the visitor's browser and adds flat shipping (`SHIPPING`). The Check out button stays off until `CHECKOUT_URL` is set up with Stripe.
