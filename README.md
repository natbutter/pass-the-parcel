# 🎁 Pass the Parcel

A simple, browser-based music player for the classic party game [Pass the Parcel](https://en.wikipedia.org/wiki/Pass_the_parcel).

No installs, no sign-ups — just open the page and hit **START MUSIC**.

## How to Play

1. **Wrap a gift** in many layers of paper (one layer per player is a good rule of thumb). Optionally hide a small treat between each layer.
2. **Sit in a circle** and give the parcel to one player.
3. **Open this page** on a phone, tablet, or laptop and press **START MUSIC**.
4. **Pass the parcel** around the circle while the music plays.
5. When the music **randomly stops**, whoever is holding the parcel unwraps one layer.
6. Press **RESUME NEXT ROUND** to start the next round.
7. The player who unwraps the **final layer** wins the prize inside!

## Features

| Feature | Details |
|---|---|
| **Random stop timer** | Configure a minimum and maximum time (in seconds) — the music will stop at a random moment in that window, so nobody can predict when! |
| **YouTube support** | Paste any YouTube link to use as the music track (desktop browsers). |
| **Built-in tracks** | Several royalty-free tracks are included if you don't have a YouTube link handy. |
| **Randomise mode** | Pick *Randomise Free Track* to shuffle between the built-in tracks each round. |
| **No install required** | It's a single HTML file — open it directly in any modern browser. |

## Getting Started

### Option 1 — Open directly

Visit [https://natbutter.github.io/pass-the-parcel/](https://natbutter.github.io/pass-the-parcel/) on desktop or mobile and play!

### Option 2 — Serve locally


Download or clone the repo, then open `index.html` in your browser:

```bash
open index.html        # macOS
xdg-open index.html    # Linux
start index.html       # Windows
```

If you want to serve it over your local network (e.g. so everyone at the party can control it from their phone):

```bash
python3 -m http.server 8000
```

Then visit `http://<your-ip>:8000` on any device on the same Wi-Fi network.

## Tips

- **YouTube on mobile:** YouTube embeds may not autoplay on some mobile browsers due to platform restrictions. Use the built-in tracks for the most reliable mobile experience.
- **Keep it fair:** Place the speaker where all players can hear it equally, and don't let the person controlling the phone peek at the timer!
- **Volume:** The built-in tracks play at 60 % volume by default. Adjust your device volume to suit the room.

## License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details. Do you want with it!
