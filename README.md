# 🎓 Math Games for Kids — Levels 1–5

A collection of self-contained math games, one per age band. Each game is a **single HTML file**: double-click to play, works offline on tablets, phones, and laptops. No installs, no ads, no links, no accounts, no data collected — parents can read every line of code.

Open `index.html` for a launcher page, or run any game directly.

## The games

| Level | Game | Ages | Skill | File |
|-------|------|------|-------|------|
| 1 | 🦖 Feed the Monster | 4–5 | Counting 1–10, number recognition | `games/level-1/feed-the-monster.html` |
| 2 | 🐠 Bubble Math | 6–7 | Addition & subtraction within 20 | `games/level-2/bubble-math.html` |
| 3 | 🚀 Space Blaster | 8–9 | Multiplication tables 2–9 | `games/level-3/space-blaster.html` |
| 4 | 🥷 Ninja Numbers | 10–11 | Mixed-operation mental-math fluency | `games/level-4/ninja-numbers.html` |
| 5 | 🎯 X Hunter | 12+ | Pre-algebra: solve for x | `games/level-5/x-hunter.html` |

## Design principles (shared by all games)

- **Age-matched design.** Input precision, reading level, color palette, difficulty tolerance, and tone all follow the age band — huge tap targets and zero reading at Level 1; dark neon palettes, hard modes, and personal bests at Levels 4–5.
- **Learning lives inside the mechanic.** The math *is* the gameplay (tapping is counting, aiming is multiplying) — never a quiz interrupting a game.
- **Silent adaptive difficulty.** Streaks quietly raise difficulty; misses quietly lower it and re-serve missed questions later (spaced repetition). Kids never see a grade label.
- **Kind failure.** No buzzers, no game-overs for young kids. Wrong answers get a wobble, a hint, or a worked solution — and the same question returns later.
- **Natural stopping points.** Rounds/waves end with a "play again?" pause so screen time can end without a meltdown.
- **Parent trust.** Every game has a ⓘ panel explaining the skill practiced, a persistent mute button, and a `TUNABLES` section at the top of the script for adjusting difficulty.

## Tuning a game

Open the game file in any text editor and edit the constants at the top of the `<script>` block, e.g.:

```js
// ===== TUNABLES (parents: adjust these!) =====
const START_COUNT = 2;   // first round asks for this many
const MAX_COUNT   = 10;  // hardest round
```

## Roadmap

- Science games per level
- Sibling/2-player modes
- PWA packaging for home-screen install; Play Store / iOS wrappers later
