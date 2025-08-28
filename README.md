Niyantri — Demo Luxury Coffee Store

Overview
- A multi-page demo online store built with Tailwind CSS utility classes in the HTML.
- Pages included: index.html, products.html, product.html, cart.html, checkout.html, about.html, contact.html.
- 10 sample products provided via products.js (placeholder images).
- Demo PayPal checkout integrated on checkout.html using sandbox client-id (`sb`).
- Cart persists in localStorage (demo only).

Features
- Responsive full-width design with a navy + gold + champagne palette.
- Add to cart, cart management, shipping-by-country calculation, demo PayPal flow.
- Contact form and newsletter/signup are mocked with in-page confirmation.

How to use
1. Open index.html in a browser. (For PayPal demo to work you need network access because it loads the PayPal SDK from PayPal.)
2. Browse Shop -> add items to cart -> go to Cart -> Checkout.
3. On Checkout, select country to see shipping rates and click the PayPal button (sandbox demo).

Notes & Defaults
- Currency: USD (demo).
- Shipping defaults (demo): US $8, Canada $12, EU $15, Rest of World $25.
- Images use placeholders in the format: `https://images.unsplash.com/photo-1588192524634-1c3f8490f68b?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w3ODkyNDZ8MHwxfHNlYXJjaHw1fHxkZXNjcmlwdGlvbnxlbnwwfDB8fHwxNzU2MzY1MzQxfDA&ixlib=rb-4.1.0&q=80&w=1080` — replace with real image URLs before production.
- Fonts: Comments at top of HTML files indicate preferred Google Fonts (Playfair Display / Inter). Replace or import the fonts in production if desired.

Files
- index.html — Home page with featured items and newsletter.
- products.html — Product listing with search and category filter.
- product.html — Product detail template (uses ?id=).
- cart.html — Cart management (localStorage).
- checkout.html — Checkout with shipping calculation and PayPal sandbox button.
- about.html — About / returns policy.
- contact.html — Contact form (demo).
- products.js — Sample product data used across pages.
- README.md — This file.

Customization
- Replace placeholder images and update PRODUCTS in products.js for real inventory.
- For a production PayPal integration, replace the PayPal SDK client-id in checkout.html with your live client id and test thoroughly.
- Add server-side handling for contact/subscription forms and secure checkout/order processing for production.

If you want, I can:
- Replace placeholders with real images you provide.
- Wire up a real payment integration (Stripe/PayPal) and backend order handling.
- Add user accounts, order history, inventory management, or promo codes.

Enjoy — this is a demo build for Niyantri (luxury coffee).