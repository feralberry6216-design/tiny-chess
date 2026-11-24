# tiny-chess

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/feralberry6216-design/tiny-chess/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/feralberry6216-design/tiny-chess/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A complete chess engine in 4,064 bytes of Python: alpha-beta search with a transposition table, quiescence, null-move pruning and piece-square-table evaluation, packed as an lzma payload in a single main.py. It plays the make.fun tiny-chess-01 gauntlet through the contest env, searching to a fixed node budget (never a clock), so every game replays move for move.

## Run it

```sh
python3 -P -s main.py   # with MAKEFUN_ENV_URL set to the contest env
```

---

<sub>Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
