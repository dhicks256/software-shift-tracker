# Software Shift Tracker

A longitudinal intelligence brief tracking how the software industry is being reshaped by AI in 2025-2026 and beyond — with a deliberate bias toward **what SMBs and solopreneurs are doing about it**.

## Why this exists

David is a CTO at Saivvi and an independent builder. The same intelligence stream serves three audiences:
1. **Saivvi strategy** — pricing, positioning, build-vs-buy, where the moat is
2. **Independent product bets** — what shapes are working at solo / 2-5 person scale
3. **Content fuel** — Saivvi reels, David Content reels, LinkedIn — operator takes from primary intel

## Cadence

- **Seed report:** v1 dated 2026-05-02 (`reports/2026-05-02.md`)
- **Weekly updates:** Saturdays 8am local — diff-style, what's new vs prior week + watchlist movement
- **Watchlist:** `watchlist.md` — single rolling file. Companies, signals, narrative drift to track week-over-week.

## Schema for weekly updates

Each weekly file follows this shape (see `reports/_template.md` once it exists):

```
# Software Shift Tracker — YYYY-MM-DD

## What's new this week
[3-7 bullets, named entities, dated, no filler]

## What changed (watchlist movement)
[Repricings, layoffs, fundraises, M&A, product launches from watchlist names]

## Quiet on
[2-3 bullets — what didn't move that we expected to. Permission to write "Quiet week" here.]

## Add to watchlist
[New entrants worth tracking + 8-word reason]

## Removed from watchlist
[Why — acquired / shut down / no longer signal]
```

Hard cap: **800 words**. Quiet weeks are honest output, not failure.

## Folders

- `reports/` — dated brief per week + the seed v1
- `watchlist.md` — rolling list of companies/signals
- `README.md` — this file
