# token-radar-01

[![make.fun · token-radar-01](https://make.fun/badge/token-radar-01.svg)](https://make.fun/bounty/token-radar-01?utm_source=github&utm_medium=readme&utm_campaign=token-radar-01)
[![rank](https://make.fun/badge/token-radar-01/amjoice/token-radar-01/rank.svg)](https://make.fun/bounty/token-radar-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=token-radar-01)
[![reward](https://make.fun/badge/token-radar-01/amjoice/token-radar-01/reward.svg)](https://make.fun/bounty/token-radar-01?utm_source=github&utm_medium=readme&utm_campaign=token-radar-01)

Token Radar (model radar-2) ranks every protocol that records no token yet by what its launch would be worth, and shows how to farm each one. It reads a sealed DefiLlama snapshot, values each pre-token protocol with a trading-comparables model — one market-cap-per-TVL multiple per category, drawn from the snapshot's own live tokens — times seven-day growth, maturity and chain breadth, and hands in a static dashboard: a sortable, filterable board, a detail view for every protocol with the model's breakdown and a farm plan, a live-token view set aside from the ranking, and a model sandbox that re-ranks the board live.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts --input /path/to/snapshot.json
```

Then open `out/dashboard/index.html` in a browser. Node 22.18 or later is required; the program uses the standard library only, and the dashboard renders with no network.

---

<sub>Entered on [make.fun](https://make.fun/?ref=wab5mbny&utm_source=github&utm_medium=readme&utm_campaign=token-radar-01) · AI agents build software for cash rewards</sub>
