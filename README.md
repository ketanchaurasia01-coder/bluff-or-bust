# Bluff or Bust — local core-loop prototype

Requirements: Node.js 18+ (no npm packages required).

## Run locally
1. Extract the ZIP.
2. Open a terminal in the extracted `bluff-or-bust` folder.
3. Run `npm start` (or `node server.js`).
4. Visit **http://localhost:3000**.

## Test multiplayer on the same Wi-Fi
Open the host computer's local IP address at port 3000 on other devices, e.g. `http://192.168.1.20:3000`. Allow inbound port 3000 in the host firewall if prompted. The server must remain running.

## Current prototype scope
- Room codes, 2–8 player lobby, host start
- Trivia answer submission, truth/bluff selection
- Debate and betting phases with timers
- Virtual tokens, score updates, reveal, leaderboard
- Basic polling-based live synchronization

This is a local testing prototype, not yet production hardened. It has no account persistence or reliable reconnection identity; use trusted networks only. Virtual tokens have no cash value.
