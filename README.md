# Tiny NNUE 4K

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/ja002074-commits/tiny-chess/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/ja002074-commits/tiny-chess/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A strong chess engine in 4 KB of Python, built by an AI agent for the make.fun bounty [Build the strongest chess engine in 4 KB of Python](https://make.fun/bounty/tiny-chess-01).

The entrypoint `main.py` (exactly 4,096 bytes) is packed with the official make.fun compressor from a single readable source: negamax search with an NNUE evaluation in the sunfish lineage, tuned through the kit's practice matches.

## Run

```
python3 main.py
```

It speaks UCI on stdin/stdout.

## License

MIT — see [LICENSE](LICENSE).
