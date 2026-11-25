# GroceryKit — Know the Price Before You Reach the Shop

GroceryKit is a weekly grocery planner for Bengaluru. Pick a store — DMart, BigBasket or your local kirana — and see what the week's basket costs there before you leave home. Everything stays on your device — no account, no uploads.

**Live:** https://abhiramunni.github.io/grocerykit/

## What it does

- **This week's basket** — 16 everyday items pre-loaded, with the total at your chosen store, a weekly-budget ring (default ₹2,000) and a cheapest-store callout. This week the Local Kirana wins at ₹1,847, saving ₹197 against BigBasket and ₹44 against DMart.
- **Pick your store** — one tap recomputes every shelf price, basket total and cheapest badge across the whole app.
- **The aisles** — 48 items across 6 aisles (Vegetables, Fruits, Dairy & Eggs, Rice & Staples, Spices & Masala, Household), each a horizontal snap-scroll shelf. Tap + or − to change quantities; tap any item for a detail sheet comparing all three stores with per-unit maths.
- **My list** — your basket grouped by aisle, the way the shop is laid out, with in-store tick-off, a running "left to buy" total, copy list, and clear-bought. Add your own items with the custom-item form.
- **Pantry first** — 8 staples on your shelf with days-left, a "use first" callout (sunflower oil, 4 days; toor dal, 6 days) and one-tap "add to list".
- **Price watch** — this week's movers: tomato, onion and potato all down about 11%; lemon up 14%.
- **What you spend** — three weeks of real bills (₹1,720 / ₹1,905 / ₹1,780) against this week's projection at your chosen store.
- **Guides** — six short explainers in plain words: MRP vs unit price, loose vs packed, buying seasonal, kirana vs supermarket, pantry first, and the ₹500 rule.
- Cinematic intro (tap to skip, quick on return visits), 3-step onboarding tour, search, copy summary, remove-samples and two-tap erase-all.

## How prices work

Prices are **indicative**, checked at Bengaluru stores in November 2026, and will move with the market — vegetables most of all. The price on your shop's shelf is the one that counts. GroceryKit is a planner, not a shop: it sells nothing and takes no orders.

Seed basket totals (hand-verified): DMart ₹1,891 · BigBasket ₹2,044 · Local Kirana ₹1,847.

## Tech

Single self-contained `index.html` (no backend, no signup, localStorage only). Warm editorial palette (ivory paper, espresso ink, bronze/amber/terracotta), Fraunces + Inter, two AI-generated warm-editorial photos with slow Ken Burns drift. The published file on GitHub Pages uses the two photos as separate repo-root `.webp` files; the local build embeds them as base64.

## Files

- `index.html` — the app (published version references `grocerykit-hero.webp` and `grocerykit-flatlay.webp`)
- `grocerykit-hero.webp`, `grocerykit-flatlay.webp` — photos
- `README.md` — this file
- `LICENSE` — MIT
