# Snake

A browser Snake game in the style of the classic Nokia 3310: green monochrome LCD look, one self-contained `index.html`, no frameworks or libraries.

## Play

Open `index.html` in any modern browser. No build step or server needed.

| Action | Desktop | Mobile |
|---|---|---|
| Move | Arrow keys / WASD | Swipe or on-screen D-pad |
| Pause / resume | Space | II button |
| Mute | M or SND button | SND button |
| Start / restart | Any key | Tap |

The high score and mute setting are saved in your browser (`localStorage`).

## Tweaking

Edit the `CONFIG` object at the top of the `<script>` in `index.html`:

- `COLS`, `ROWS`: grid size in cells
- `CELL_SIZE`: largest cell size in px (the board shrinks to fit smaller windows)
- `START_INTERVAL`: ms per move at the start (lower is faster)
- `SPEED_STEP`: ms taken off per food eaten
- `MIN_INTERVAL`: top speed cap
