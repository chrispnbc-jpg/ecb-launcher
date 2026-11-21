# ECB PC ads

The Microsoft Store (PC) versions of ECB's mobile games read `pc_ads.json` from this folder to pick
the offers they show: ECB house ads (our games, the ECB Game Launcher, early access) mixed with
ECB affiliate offers. QR pictures sit next to it. Public player-facing files only: no keys or builds.

To turn on a game's ad once it's public on Google Play, set `"enabled": true` on its `game-<id>` entry.
When it's also on the Microsoft Store, add a second QR: `{"label": "Get it for PC", "img": "qr_<id>_pc.png"}`.
Each game hides its own ad automatically.
