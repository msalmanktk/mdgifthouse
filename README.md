# M&D Gift House — Concept C Homepage

A vanilla HTML, CSS and JavaScript storefront foundation for M&D Gift House.

## Run locally

1. Extract the ZIP.
2. Open the folder in VS Code.
3. Run `index.html` with the Live Server extension (recommended), or serve the folder with any static web server.

## Homepage design

- Concept C: bright warm cream, botanical green, champagne and gold.
- Honey is a primary homepage collection, followed by honey product cards.
- Fragrance collection uses a 3-column desktop product grid and responsive mobile layout.
- Includes customer experiences placeholder cards, FAQ accordion, Giving Back banner, contact CTA and floating WhatsApp button at bottom-right.
- Light/dark theme toggle and mobile navigation are included.

## Configuration

Edit `js/config.js` to set:
- `whatsappNumber`: international format, digits only (e.g. `923001234567`).
- `contactEmail` and `phoneDisplay`.
- Product names and prices. Current prices are sample values and must be confirmed before launch.

The WhatsApp button opens a prefilled message. If no number is configured, WhatsApp will let the visitor choose a contact.

## Images and videos

The homepage currently uses direct Unsplash image URLs as temporary stock imagery. Replace them with M&D's original product photography when available. The supplied M&D videos remain in `assets/videos/` for use across the site.

## Important scope note

This is a front-end prototype. Order/contact forms prepare WhatsApp messages; there is no live payment processing, customer database, authentication, or admin panel yet. A `.env` file is only meaningful once a backend/build process is introduced; admin-editable product and content settings should later live in a database behind a secure API.
