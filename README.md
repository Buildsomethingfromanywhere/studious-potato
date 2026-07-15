# 🎓 Math Games for Kids — Levels 1–5

A collection of self-contained math games, one per age band. Each game is a **single HTML file**: double-click to play, works offline on tablets, phones, and laptops. No installs, no ads, no links, no accounts, no data collected — parents can read every line of code.

Open `index.html` for a launcher page, or run any game directly.

## The games

| Level | Ages | Game | Skill |
|-------|------|------|-------|
| 1 | 4–5 | 🦖 Feed the Monster | Counting 1–10, number recognition |
| 1 | 4–5 | 🔺 Shape Friends | Shape & color recognition |
| 1 | 4–5 | 🐞 Bug Count | Counting & numeral matching |
| 2 | 6–7 | 🐠 Bubble Math | Addition & subtraction within 20 |
| 2 | 6–7 | 🃏 Memory Pairs | Number bonds + working memory |
| 2 | 6–7 | 🐘 Pattern Parade | Patterns & number sequences |
| 3 | 8–9 | 🚀 Space Blaster | Multiplication tables 2–9 |
| 3 | 8–9 | 🍕 Pizza Fractions | Fractions (visual) & equivalents |
| 3 | 8–9 | 🏎️ Speed Tables | Times-table fluency vs. the clock |
| 4 | 10–11 | 🥷 Ninja Numbers | Mixed-operation speed math |
| 4 | 10–11 | ⚖️ Fraction Frenzy | Comparing fractions |
| 4 | 10–11 | 🛸 Prime Patrol | Primes & factorization |
| 5 | 12+ | 🎯 X Hunter | Pre-algebra: solve for x |
| 5 | 12+ | 📐 Order of Ops | PEMDAS / order of operations |
| 5 | 12+ | 🏷️ Percent Panic | Percentages, discounts, reverse % |

Files live at `games/level-N/<game-name>.html`. The landing page (`index.html`)
has a level picker that groups games by age band, each with its own design
language (bright primaries for 4–5, coordinated themes for 6–9, dark neon for 10+).

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
