# Ray J

I build small, free tools that each answer one question well — no sign-up, no paywall, no "premium tier" hiding the useful part.

Most of them publish their numbers, so the figures on the page can be recomputed from the data repos below.

## Tools

| Tool | What it answers |
|---|---|
| **[TraceCub](https://tracecub.com/)** | Printable name tracing worksheets, sized in millimetres to real print dimensions |
| **[WaxWeigh](https://waxweigh.com/)** | Candle wax math — how much wax per jar, how many candles a bag actually makes |
| **[DnD Name Forge](https://dndnameforge.com/)** | D&D name generators that publish their pool size and duplicate rate |
| **[Band Name Check](https://bandnamecheck.com/)** | Is this band name taken? Four sources, one report |

## Open data behind them

- [candle-math](https://github.com/RayJ7/candle-math) — wax densities and yield tables used by WaxWeigh
- [dnd-name-forge-pools](https://github.com/RayJ7/dnd-name-forge-pools) — measured name-pool statistics for the D&D generators
- [bandnamecheck-data](https://github.com/RayJ7/bandnamecheck-data) — 2,075-name availability snapshot across four sources
- [letter-formation-toolkit](https://github.com/RayJ7/letter-formation-toolkit) — stroke counts and print geometry for A–Z

## How they're built

Static HTML, hand-written CSS, no framework, no build step at runtime. Hosted on Cloudflare. The only script on the page is the tool itself.
