# digital-game-store

Digital store for HTML5 games and code products.

## Structure
- `index.html` → Home (storefront + demo modal)
- `products/`
  - `boo-game/`
    - `preview/index.html` → Demo preview (runs in iframe)
    - `index.html` → Product details page (to be added next)

## Important
- Sell only content you own or have the right to resell (license).
- For secure “download only after payment”, add PayPal verification (Webhook/Serverless). Static sites alone cannot fully protect download links.

## How to add a new product
Later you will:
1. Create a folder under `products/<product-id>/`
2. Add `preview/index.html`
3. Add `products/<product-id>/index.html`
4. Add the product entry inside `PRODUCTS` array in `index.html`
