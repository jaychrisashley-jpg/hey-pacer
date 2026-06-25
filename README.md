# Hey Pacer

Public site for the Pacer Search page, deployed on Railway from this GitHub repo.

- `index.html` — the live homepage (Pacer Search)
- `Pacer Search.html` — original bundler export of the homepage (backup)
- `TrustPixel_Checkout__standalone_.html` — Stripe authorization-hold checkout page (reads the order from query params)

## How it deploys

Railway watches the `main` branch. Every push to GitHub triggers an automatic redeploy.
The site is served as static files via [`serve`](https://www.npmjs.com/package/serve) (`npm start`).

## Local preview

```bash
npm install
npm start
# open http://localhost:3000
```
