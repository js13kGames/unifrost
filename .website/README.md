---
genres:
  - platformer
  - adventure
# See github.com/js13kGames/hello-world for supported frontmatter
post: "https://nallebeorn.se/blog/js13k2026-post-mortem/"
---

Gallop, leap, and fling yourself across the clouds in search of the seven lost shards of the Bifrost in this 3D platformer!

## Controls
* Move: **WASD** (or equivalent locations on your keyboard layout)
* Jump: **SPACE** (press again in the air to create rainbows when unlocked)
* Move camera: **Mouse**

The game *should* be playable-ish with a touchpad, as you don't really need to control the camera and move at the same time (though it can help).

## System requirements
The game runs fine on latest stable Chromium and Firefox (text box looks slightly different on Firefox due to not supporting  `corner-shape`  yet).  It's most well-tested in Chromium on Linux. Not mobile-friendly, unfortunately.

The game's renderer and physics aren't particularly optimized (other than for size). It's possible that older or weaker machines may struggle running the game at full speed, in which case... sorry about that! The game tries to run at a fixed 60FPS regardless of screen refresh rate.

## Attribution
This games makes use of Frank Force's fantastic
[ZzFX](https://github.com/KilledByAPixel/ZzFX) sound engine to power the game's
very hastily added sound effects.

### Playtesters
Special thanks to Albin, Amanda, Hirad, Mirjam, and Sebastian for trying out
the various early drafts of my game and giving feedback.

## AI disclosure
No AI was involved with any of the game's design, art, audio or dialogue.
I regularly used a chatbot to help answer questions about APIs, algorithms and
language details. One function was predominantly LLM-generated.
I used no agentic AI.

## Wavedash
[https://wavedash.com/games/unifrost](https://wavedash.com/games/unifrost)

Includes a few achievements and a speedrun leaderboard.
