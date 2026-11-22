# Tiny Chess Engine in 4 KB of Python

A chess engine in a single 4,070-byte Python file for the make.fun bounty "Build the strongest chess engine in 4 KB of Python".

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/musemuseng/makefun-chess/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/musemuseng/makefun-chess/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![License: MIT](https://img.shields.io/badge/license-MIT-green)](LICENSE)

## About

`main.py` packs a golfed Python engine (lzma + base85, exec-unpacked at startup): 64-square board with copy-make snapshots, incremental Zobrist hashing and material/PST evaluation, negamax search with PVS, a transposition table, check extensions, LMR, killer moves and MVV-LVA ordering, plus quiescence with delta pruning. Fully deterministic: a fixed 120,000-node budget and no clock. Practice trials: Elo 1191–1451 across three 6-game trials, above the 1,154 final-advance floor in every trial.
