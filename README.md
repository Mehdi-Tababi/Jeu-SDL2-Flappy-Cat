# Jeu-SDL2-Flappy-Cat
Fluppy Cat is a Flappy-style 2D game written in C with SDL2. Fly a cat through moving-gap pipes, survive monsters, shoot projectiles to earn extra lives, and reach a Final Destination portal to advance levels. Includes Pause + Settings (Easy/Normal/Hard), pattern-based obstacle spawning, screen shake + hit-stop feedback, HUD, and best score saving.
# Fluppy Cat 🐱🎮 (SDL2 / C)

Fluppy Cat is a Flappy-style 2D game built in **C** using **SDL2** (+ SDL_ttf, SDL_mixer).  
You control a flying cat, avoid moving-gap pipes and monsters, shoot projectiles to defeat monsters (gain +1 life, capped), and reach the **Final Destination** portal to progress to the next level.

## Features
- 🧠 Game states: Menu / Settings / Playing / Pause / Game Over
- ⚙️ Difficulty modes: **Easy / Normal / Hard**
- 🚧 Moving-gap pipes + pattern-based spawn director
- 👾 Monsters (collision damage)
- 🔫 Projectiles (Option B): kill monsters → +1 life (max life cap)
- 🎯 Level progression + “Final Destination” portal
- 💥 Screen shake + hit-stop on impacts
- 🧾 HUD: score / level / lives / progress + best score saved locally (`best_score.txt`)
- 🔊 Sound effects (SDL_mixer) *(optional, if enabled in your build)*

## Controls
- **Space** / **Left Click**: Flap
- **K** / **Right Click**: Shoot
- **ESC**: Pause / Back

## Requirements
- SDL2
- SDL2_ttf
- SDL2_mixer

## Build (CMake)
```bash
cmake -S . -B build
cmake --build build
