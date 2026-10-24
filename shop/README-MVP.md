# M&L Swim Tailor — MVP v1

**This is a file ready for Kenneth to upload. It is NOT live on GitHub yet.**
To publish: upload `index.html` and the whole `assets/` folder to the same GitHub repository (keeping `index.html` at the root and `assets/` beside it), then enable GitHub Pages for that repository.

## What is in the MVP

- Brand: M&L Swim Tailor, custom swim caps. No brand-origin explanation is on the page.
- Language: English only. Prices: USD only. Payment: PayPal only.
- Hero cap: Seamless Racing Custom Cap — US$21.
- 13 printed-design caps — US$28 each (see mapping below).
- Page structure (structure only; no text, photos, testimonials, or prices copied from other shops):
  trust strip, easy-to-order headline, product grid by style/fit, printed sample gallery,
  short buyer guides (silicone vs latex vs lycra, fit, care), simple customer order flow, FAQ.
- Customer-facing tone only: choose cap/design, send idea, get confirmed total + preview, pay, receive cap.
- Shipping: only this line is stated — "Shipping charged separately, confirmed before payment, by destination" — and delivery about 3–4 weeks. No carrier rates and no free-shipping threshold are published.
- PayPal: real link https://www.paypal.com/qrcodes/p2pqrc/25W8DFW89EYRG and QR image `assets/paypal-qr.jpg`.
  The page states clearly that the payer enters the confirmed total amount, and the link does not pre-fill it.
- Product photos: the photos Kenneth provided, cropped to the cap/design only in the files in `assets/`.
  No app interface, listing prices, seller information, or listing numbers appear in those cropped files.
- Two hero lines, clarified 25 Oct 2026: Seamless Racing Custom Cap (US$21) is the hero of the seamless line. Underwater Fish World (US$28) is the hero of the colour ready design line — featured at the top of the Printed designs section, not as the overall site hero or as the seamless hero cap.

## What is deliberately left out

- Non-cap products (towel, goggles accessories) — no confirmed prices, so they are not in the MVP.
- Other languages, other currencies, and other payment methods — MVP v1 is English / USD / PayPal only.
- Internal business steps — none of those appear on the customer page.
- Fake testimonials, fake customers, and prices presented as real when they are not — none are in the MVP.
- The branded-character design that was held out pending a licence check — it is NOT in the MVP.

## THE ONE placeholder to replace before go-live

**Placeholder: `ORDER_FORM_URL`**

Exact locations in `index.html`:

1. Top HTML comment (near the top of the file):
   `<!-- Order form placeholder: ORDER_FORM_URL -->` and the comment above it explaining the replacement.
2. Every order button `href` — search the file for `href="ORDER_FORM_URL"` and replace every occurrence
   with your real order form link. This includes the header button, the hero button, the hero-cap button,
   all 13 printed-design buttons, and the footer link.

Do NOT go live with `ORDER_FORM_URL` still in the file, and do NOT replace it with a made-up link.
The PayPal link above is real and does not need replacing.

## Image-to-design mapping (all confirmed by viewing the provided photos)

| Product card | File in `assets/` | Source photo viewed |
|---|---|---|
| Cheeky Monkey "I Love Swimming" — US$28 | `cheeky-monkey.jpg` | media_library/image/7a/… |
| Underwater Fish World — US$28 | `underwater-fish-world.jpg` | media_library/image/c2/… |
| Bunny Girl — US$28 | `bunny-girl.jpg` | media_library/image/b2/… |
| Nine-Tail Fox — US$28 | `nine-tail-fox.jpg` | media_library/image/6c/… |
| Cranes in Spring — US$28 | `cranes-in-spring.jpg` | media_library/image/0d/… |
| Cranes in Flight — US$28 | `cranes-in-flight.jpg` | media_library/image/b3/… |
| Blue Dragon — US$28 | `blue-dragon.jpg` | media_library/image/08/… |
| Phoenix Rising — US$28 | `phoenix-rising.jpg` | media_library/image/a1/a142… |
| Butterfly Wings Spread — US$28 | `butterfly-wings-spread.jpg` | media_library/image/e9/… |
| Butterflies Among Flowers — US$28 | `butterflies-among-flowers.jpg` | media_library/image/ae/… |
| Butterfly & Dewdrops — US$28 | `butterfly-and-dewdrops.jpg` | media_library/image/69/… |
| Summer Butterfly Dance — US$28 | `summer-butterfly-dance.jpg` | media_library/image/04/… |
| Blue Butterfly Dream — US$28 | `blue-butterfly-dream.jpg` | media_library/image/2b/… |

**Uncertain mappings: none.** Each of the 13 mappings above was confirmed by the design visible in the photo
(and, where the photo carried a design label, by that label). The branded-character photo and the multi-cap
overview photo were deliberately excluded, not used as a product card.

## Verification done

- All image files referenced in `index.html` exist in `assets/`.
- Hero price is US$21; every printed design is US$28.
- No internal business wording, no app-interface prices, and no held-out branded design appear on the page.
- `assets/paypal-qr.jpg` is the PayPal QR image Kenneth provided.
