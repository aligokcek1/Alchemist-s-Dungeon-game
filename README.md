# Alchemist's Dungeon

**[➡️ Play the game here! ⬅️](https://aligokcek1.github.io/Alchemist-s-Dungeon-game/)**

A retro-style, desktop-focused platformer game built with pure Vanilla JavaScript, HTML, and CSS, styled with Tailwind CSS for a modern UI polish. All assets and logic are contained within a single HTML file, making it a portable and impressive showcase of web development skills.

<img width="1424" alt="Screenshot 2025-06-11 at 16 33 25" src="https://github.com/user-attachments/assets/ce394692-9e9c-4ec0-867c-5e71a8c47778" />

## Features

- **Advanced Procedural Generation:** Every playthrough features a unique, algorithmically generated dungeon. The generation logic includes a reachability analysis to ensure every level is winnable and fair.
- **Rich Audio Experience:**
    - Background music to set a retro, mysterious tone.
    - Sound effects (SFX) for jumping, landing, collecting items, taking damage, and more.
    - Separate UI controls to mute music and SFX independently.
- **Dynamic Player Character:** A pixel-art alchemist character with fluid animations for idling, running, jumping, and landing (squash-and-stretch).
- **Engaging Gameplay Loop:**
    - Collect all the gems to win the game.
    - Pick up **Health Potions** to restore health and survive longer.
    - Avoid spike traps and intelligent, patrolling enemies.
    - Game pauses on "Game Over" or "You Won" screens with unique audio cues.
- **Polished User Experience:**
    - A sleek, animated loading screen on first launch.
    - An instruction screen before the game starts.
    - A dynamic, animated background that gives the page a "mystic retro flow."
- **Rich Visuals & Effects:**
    - Retro CRT screen effect and glowing "neon" text.
    - Screen shake effects on damage and level resets.
    - A dynamic minimap that shows the entire dungeon, the player's position, and key items.
    - A particle system for jump effects, damage indicators, and item collection.

## How to Play

You can play the game directly in your browser by visiting this link:

**[https://aligokcek1.github.io/Alchemist-s-Dungeon-game/](https://aligokcek1.github.io/Alchemist-s-Dungeon-game/)**

Use **WASD** to move and the **Spacebar** to jump.

---

### For Local Development

If you want to run the game locally:

**Important:** Because this game loads local audio files, you must run it from a local web server due to browser security policies.

1.  Clone or download this repository.
2.  Make sure you have all the sound files in the `assets/audio` directory.
3.  From the root directory of the project, start a local web server. If you have Python installed, you can run:
    ```bash
    # For Python 3
    python -m http.server
    ```
4.  Open your browser and navigate to `http://localhost:8000/index.html`.

## Tech Stack

- **Core Game:** Vanilla HTML, CSS, and JavaScript.
- **Audio:** Howler.js for robust sound and music management.
- **Styling:** Tailwind CSS for the UI elements outside the game screen.
- **Font:** "Press Start 2P" from Google Fonts. 
