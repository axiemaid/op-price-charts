# OP Hyper Battle Price Charts

Price tracker for One Piece Hyper Battle Carddass (1999) cards — scatter plot with grade-based color coding, trend lines, and sale history.

## Cards Tracked

- **S03** — ゴムゴムの実 (Gomu Gomu no Mi)

## Data

Sales data is in `sales.json`, sourced from Mercari Japan sold listings. Each entry includes:
- `item_id` — Mercari listing ID
- `title` — listing title
- `price_jpy` — sold price in yen
- `sold_date` — date of sale
- `grade` — condition grade (A/B/C/D)

## Grading

| Grade | Condition |
|-------|-----------|
| A | Near Mint |
| B | Good |
| C | Fair |
| D | Poor |

## View

Open `index.html` in a browser or host via GitHub Pages.
