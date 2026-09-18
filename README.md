# Chess 2.0

Four-player free-for-all chess in a single HTML file. Red → Blue → Yellow → Green
on a 14×14 cross board. No install, no accounts, no build step.

**Play:** https://sammynashed.github.io/chess-2/

- **Online** — everyone opens the same room code (or an invite link). Moves travel
  over a public MQTT broker, so there is no game server to run; the page itself is
  a static file.
- **Offline** — hot-seat for four at one screen, or fill the empty seats with bots.
- **Bots** — paranoid alpha-beta search with a quiescence pass, three strengths.
  They take free material, decline poisoned pieces, and hunt exposed kings.
- **Your colour always faces you** — the board rotates per player, locally.
- Lose your king and your whole army leaves the board. Last player standing wins.

Piece artwork: the Cburnett SVG set from Wikimedia Commons (CC BY-SA 3.0),
fetched at runtime and recoloured as CSS masks.
