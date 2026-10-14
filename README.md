# Gambit Chess

A browser-based chess game with smooth animations, built with HTML, CSS and JavaScript.
Chess rules are handled by the chess.js library.

## Features
- Two modes: Player vs Player (same device) and Player vs AI (Easy, Medium, Hard)
- Full chess rules: check, checkmate, stalemate, castling, en passant, promotion
- Draws: threefold repetition, fifty-move rule, insufficient material
- Click-to-move and drag-and-drop, with legal-move highlights
- Animated moves, captures and check warning; last-move highlight
- Move history, captured pieces, undo, restart, flip board
- Optional chess clock (3, 5 or 10 minutes)
- Sound effects, and settings for animations, sound and move hints
- Game-over screen with Play again and Review game
- Works on desktop and mobile

## How to run
1. Download this project and keep `index.html` on your computer.
2. Double-click `index.html` to open it in Chrome, Safari or Firefox.
3. An internet connection is needed (the chess.js library loads from a CDN).

## Controls
- Click or drag a piece to move it
- U = undo, F = flip board, Left/Right arrows = review moves

## Tech
HTML, CSS, JavaScript, chess.js 0.10.3. The AI is a custom alpha-beta search.
