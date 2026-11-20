# tiny-chess-4kb

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/1touhou/tiny-chess-4kb/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/1touhou/tiny-chess-4kb/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A 4 KB Python chess engine: alpha-beta search with quiescence, a transposition table and null-move pruning, searching a fixed budget of 60,000 nodes per move. It plays games through the make.fun environment and never uses a clock or unseeded randomness.

## Strength

In local practice trials against the kit's gauntlet it scored Elo 1,279 (3 wins out of 6), above the 1,154 floor.

## Run it

```sh
python3 -P -s main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=3bes5xfn&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
