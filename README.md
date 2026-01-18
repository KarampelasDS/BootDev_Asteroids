# Asteroids Clone

A simple Asteroids-style arcade game built with `pygame` for Boot.Dev.  
You control a ship, dodge and destroy incoming asteroids, and watch them split into smaller, faster pieces.

---

## Features

- Player-controlled ship with rotation and thrust
- Shots that destroy asteroids
- Asteroids that:
  - Spawn in random positions
  - Drift through space with random velocities
  - Split into smaller asteroids when shot
- Logging of game events (e.g. asteroid splits) to `game_events.jsonl`

---

## Requirements

- Python 3.10+ (recommended)
- `pygame`

Install dependencies (if using `pip`):

```bash
pip install -r requirements.txt
# or, if using pyproject.toml / poetry:
# poetry install
