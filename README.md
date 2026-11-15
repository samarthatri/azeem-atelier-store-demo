# Azeem Atelier ecommerce demo

A responsive, buildless storefront concept for medieval armour, shields, accessories and vintage brass lighting.

## Preview

Serve `dist/` with any static web server. No dependencies or build step are required. For example, run `npx serve dist` with Node.js installed.

## Included

- Five concept products with details and finish/style selection
- Search, category filters, sorting and saved products
- Browser-local persistent cart, quantity changes and removal
- Buy now and add-to-bag actions
- USD, CAD, GBP and INR display using fixed demo conversion rates
- USA, Canada and UK sample shipping calculations
- Validated demo checkout and order confirmation
- Responsive desktop and mobile layouts, native modal dialogs and keyboard focus styles

## Reference analysis

The original reference, https://azeem-atelier.vercel.app/, is a heritage-themed enquiry catalogue. It uses cream, forest green, brass accents, serif headlines, concept photography and category-led browsing. It has enquiries and saved enquiry pieces but no priced cart-to-checkout purchase flow.

Etsy, https://www.etsy.com/, supplies useful commerce patterns: a prominent search field, category navigation, product cards with visible prices, favorites and cart access. This demo adapts those patterns to a single-brand boutique rather than reproducing Etsy’s marketplace design.

## Before a real launch

Replace concept images and sample product data in `dist/app.js` with approved inventory. Confirm business branding, contact details, prices, dimensions, product use, lighting electrical specifications, and stock. Connect a commerce backend, payment provider, order handling and shipping rates. Provide approved shipping, returns and privacy policies. Validate destination-specific product eligibility and duties/taxes. This demo does not implement those production services.

No payment details are requested or collected. Checkout entries are not sent or persisted. Cart and favorites use browser localStorage. Currency conversion rates and shipping are illustrative. Source concept imagery is reused from the user-supplied reference demo.

## Files

- `dist/index.html`: page structure
- `dist/style.css`: responsive design
- `dist/app.js`: catalogue and storefront interactions
- `dist/assets/`: local concept images
- `.openai/hosting.json`: private Sites hosting identity

## Verification

JavaScript syntax check passed. Browser checks covered product details, adding to bag, quantity/subtotal updates, country-based shipping totals and successful sample checkout. Desktop and mobile layouts were visually reviewed.
