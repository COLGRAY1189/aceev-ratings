# AceEV ratings feed

Weekly-refreshed tennis rating snapshots consumed by the AceEV app at startup.
Built from free public data (tennis-data.co.uk results, UTS serve stats) by a
scheduled GitHub Action. Data files only — no application code lives here.

- `elo-ratings.json` — surface-adjusted Elo + world ranking per player
- `serve-ratings.json` — serve/return point-win rates (ATP)
