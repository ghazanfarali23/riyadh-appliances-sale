# Riyadh Appliances & Furniture Sale

Static sale page (single `index.html` + `assets/`). No build step.

## Deploy on Coolify

1. New Resource → Public Repository → `https://github.com/ghazanfarali23/riyadh-appliances-sale`
2. Build Pack: **Static** (or Nginx)
3. Publish Directory: `/`
4. Deploy. Attach your domain if you want one, otherwise use the Coolify-generated URL.

## Updating listings

Edit the `ITEMS` data in `index.html` (or ask Muse) and push — Coolify redeploys automatically if the webhook is enabled.

- Mark an item sold: set its `"sold"` field to `true`.
- Prices: `"retail"` shows struck through, `"price"` is the asking price. `null` price = "Price on request".
