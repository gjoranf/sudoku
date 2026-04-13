# Sudoku

A modern, single-file Sudoku game. No dependencies, no build step — just open `index.html`.

**Play it live:** [gjoranf.github.io/sudoku](https://gjoranf.github.io/sudoku/)

## Features

- Three difficulty levels (Easy / Medium / Hard)
- Dark and light theme with toggle
- Score system: `base points - time - errors × 200`
- All-time best record per difficulty (localStorage)
- Visual feedback when completing rows, columns, boxes, or all 9 of a number
- Undo and erase
- Full keyboard support (arrows, digits, Delete, Ctrl+Z)
- Mobile responsive with touch-optimized controls

## Controls

| Input | Action |
|-------|--------|
| Click/tap cell | Select |
| 1–9 | Place number |
| Delete / Backspace | Erase cell |
| Ctrl+Z | Undo |
| Arrow keys | Navigate |

## Scoring

| Difficulty | Base points |
|------------|-------------|
| Easy | 1000 |
| Medium | 2000 |
| Hard | 3000 |

Final score = `max(0, base - seconds elapsed - errors × 200)`

## Tech

Single HTML file with embedded CSS and JavaScript. Zero dependencies.
