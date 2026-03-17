# Epstein Dash

A 3D endless runner game built with Three.js. Run through a tropical island, dodge obstacles, and collect classified files before the zombie catches you.

**Play it live:** [https://aurabagz.github.io/epstein_dash/](https://aurabagz.github.io/epstein_dash/)

## Gameplay

- Dodge obstacles (rocks, barriers, cones) while running down a sandy island road
- Collect Epstein Files to increase your score
- Build combos by collecting files in quick succession
- Collect 50 files to win
- Don't let the zombie catch you!

## Controls

| Input | Action |
|-------|--------|
| Arrow Keys / WASD | Move left/right |
| Space | Jump |
| Swipe (mobile) | Move / Jump |

## Tech Stack

- **Three.js** (r162) - 3D rendering via ES module CDN
- **Vanilla HTML/CSS/JS** - Single-file game, no build step required
- **Web Audio API** - Sound effects and music

## Project Structure

```
epstein_dash/
  index.html              # Game (HTML + CSS + JS)
  assets/
    images/
      dor_bros_logo.png    # Loading screen logo
      start_screen.png     # Start screen background
      favcon.png           # Browser tab icon
      busted_screens/      # Game over screen layers (0-5.5)
    audio/
      music.mp3            # In-game background music
      intro.mp3            # Start screen music
      gameover.mp3         # Game over sound effect
      gameover2.mp3        # Alternate game over sound
      combo.mp3            # Combo pickup sound
      combo40.mp3          # High combo sound
    video/
      wow2.mp4             # Win condition video
```

## Running Locally

Serve the project directory with any static file server:

```bash
npx http-server . -p 8080
```

Then open `http://localhost:8080` in your browser.

## Credits

Built by [The Dor Brothers](https://www.thedorbrothers.com)
