# agenatus-prices

Public price list that the Agenatus daemon fetches to price engine turns as API-equivalent USD.

- `agenatus-prices.json` — the document. `version` is `YYYY-MM-DD.N`; a daemon applies a file only when its version is newer than what it has.
- Prices are per million tokens, as decimal strings, from the vendors' official pages listed per row in `sourceUrl`.
- Updated by hand. Turns already priced are never recomputed; only turns without a price pick up a new row.
