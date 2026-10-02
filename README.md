# Adversarial Game AI

A small two-player game environment used to demonstrate **minimax search**, **alpha-beta pruning**, and heuristic evaluation.

## Use case

Competitive decision-making is useful beyond games. The same adversarial-search pattern applies when another actor has objectives that conflict with yours and can respond strategically.

## Agent pipeline

```text
Game State
   |
   v
Generate Actions
   |
   v
Minimax Search
   |
   +--> Alpha-Beta Pruning
   |
   v
Heuristic Evaluation
   |
   v
Selected Move
```

## What to measure

- chosen move
- search depth
- nodes expanded
- nodes pruned with alpha-beta

## Run

```bash
python examples/demo.py
```

## Tests

```bash
pytest -q
```

## CS221 connection

Inspired by adversarial-search concepts commonly covered in CS221. The game environment, solver, and experiments are independently developed.

## GitHub metadata

**Repository name:** `adversarial-game-ai`

**Description:** A game-playing agent using minimax, alpha-beta pruning, and heuristic evaluation for adversarial decision making.

**Topics:** `artificial-intelligence` `game-ai` `minimax` `alpha-beta-pruning` `adversarial-search` `python` `algorithms` `cs221`
