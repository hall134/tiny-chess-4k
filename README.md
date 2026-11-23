# tiny-chess-4k

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/hall134/tiny-chess-4k/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/hall134/tiny-chess-4k/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A complete chess engine in 4,036 bytes of Python. Negamax alpha-beta search with a transposition table, null-move pruning, late-move reductions, check extensions and quiescence search, over a tapered piece-square-table evaluation with incremental score updates. The board is kept from the side to move's point of view and rotated after every move, so one set of tables serves both colours. Move choice is driven by a fixed node budget — never a clock — so every game is deterministic and replays move for move. `main.py` is the readable engine source packed with the kit's own `compress` command; everything the engine needs is inside its own bytes.

## Run it

```sh
MAKEFUN_ENV_URL=<trial env url> python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=mprnyccw&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
