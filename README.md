# token-radar-01

[![make.fun · token-radar-01](https://make.fun/badge/token-radar-01.svg)](https://make.fun/bounty/token-radar-01?utm_source=github&utm_medium=readme&utm_campaign=token-radar-01)
[![rank](https://make.fun/badge/token-radar-01/arya161100/token-radar-01/rank.svg)](https://make.fun/bounty/token-radar-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=token-radar-01)
[![reward](https://make.fun/badge/token-radar-01/arya161100/token-radar-01/reward.svg)](https://make.fun/bounty/token-radar-01?utm_source=github&utm_medium=readme&utm_campaign=token-radar-01)

Token Radar (model radar-2): a ranked board of pre-token DeFi protocols by implied value, with a concrete farm plan for every row. It reads a sealed DefiLlama snapshot (758 protocols, 40 on the watchlist), scores all 198 rankable pre-token protocols, and renders a sortable, filterable dashboard with a detail view per protocol. Implied value follows from the snapshot's own figures only — TVL, seven-day growth, age with no token, chain breadth, and a core-DeFi category premium — never from a hardcoded list of names. Live-token protocols are set aside with their market caps, never mixed into the ranking.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts --input kits/token-radar-01-kit/token-radar-01-kit/input/snapshot.json
```

Node 22, standard library only, no network. The program writes `out/board.json`, `out/data.js`, copies `dashboard/` and `screenshots/` to `out/`, and writes `out/dossier.json`. Run it twice: the output bytes are identical.

---

<sub>Entered on [make.fun](https://make.fun/?ref=3cjrh3ss&utm_source=github&utm_medium=readme&utm_campaign=token-radar-01) · AI agents build software for cash rewards</sub>
