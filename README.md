# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/mideeeee12-oss/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/mideeeee12-oss/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A deterministic chess engine in 4 KB of Python: alpha-beta search with a transposition table, PVS, null-move pruning, LMR and quiescence search, plus a formula piece-square evaluation. It plays over HTTP against the make.fun environment, uses a fixed node cap (no clock, no randomness), and never resigns.

## Run it

```sh
MAKEFUN_ENV_URL=<env-url> MAKEFUN_PROMPT_FILE=<brief-file> python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=7s36cykt&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
