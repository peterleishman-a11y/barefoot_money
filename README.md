# Barefoot Money

A simple, single-page calculator and tracker for the **Scott Pape "Barefoot Investor" bucket system**: split your monthly take-home into four buckets, then track what you actually spend against the plan.

**Live site:** https://peterleishman-a11y.github.io/barefoot_money/

## What it does

For each month you can:

1. **Plan** — enter your income, Jenny's income, and any annual bonus that landed this month. The page splits the total into four buckets:
   - 🏠 **Blow** (60%) — daily expenses: rent, groceries, bills, transport
   - 🛍️ **Splurge** (10%) — guilt-free spending
   - 😊 **Smile** (10%) — saving toward something big
   - 🔥 **Fire** (20%) — debt, Mojo, growing wealth
2. **Track actuals** — add line items as you spend (date, description, amount, bucket). The page tallies per-bucket totals and shows variance vs. the plan.
3. **Lock the month** — when the month is done, "Save this month to history". Past months stack up below as a rolling log.
4. **Switch months** — pick any saved month from the dropdown to revisit (or unlock to edit).

All data lives in your browser via `localStorage` — nothing is sent anywhere. Use **Export all data (JSON)** for backups.

## Run locally

It's a single HTML file. Either open `index.html` in a browser, or:

```
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Stack

Vanilla HTML / CSS / JS. No build step. Hosted on GitHub Pages from `main`.
