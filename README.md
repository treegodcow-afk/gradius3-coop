# Gradius III Co-op

A browser page that adds simultaneous 2-player co-op to *Gradius III* (SNES, USA version).

This repository contains **no game data**: only the web page and a small IPS patch with the co-op changes.
To host a game you need your own dump of `Gradius III (USA).sfc` (SHA-1 `7e62203a4198e9404eb7b076802c09786e5a63f4`).
The page checks the file, applies the patch in your browser, and runs it with [snes9x-wasm](https://github.com/wasm-gaming/snes9x-wasm)
(snes9x's license allows non-commercial use only).

- **Same keyboard:** player 1 uses arrows, X/Z/S/A, Enter. Player 2 uses I/J/K/L, N/B/H/G, and presses 2 to join.
- **Online:** click "Invite a friend online" and send the link. Your game streams to them, and they fly player 2. They don't need the game file.
