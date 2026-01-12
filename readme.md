# Pig Game (Dice Game)

A simple 2-player dice game built with vanilla JavaScript and DOM manipulation.

## Gameplay Rules

- There are **2 players**: Player 1 (0) and Player 2 (1).
- On your turn, click **Roll Dice**:
  - A random dice value from **1–6** is generated.
  - If you roll **2–6**, it’s added to your **current score** (turn total).
  - If you roll a **1**, you **lose your current score** for that turn and the turn switches to the other player.
- Click **Hold** to:
  - Add your current score to your **total score**.
  - Then the turn switches to the other player.
- The first player to reach **100+ total score** wins.
- Click **New Game** to reset everything.

## Features

- Turn-based gameplay with active player highlighting
- Current score resets on rolling `1` or after holding
- Winner state styling when a player reaches 100 points
- Dice image updates dynamically (`dice-1.png` ... `dice-6.png`)
- Full game reset via `New Game`
