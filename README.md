#   Shadow Blade — Samurai Fighter

A fast-paced 2D samurai duel built using HTML5 Canvas, featuring fluid combat, adaptive AI, and a striking Japanese ink art aesthetic.

---

##   Overview

**Shadow Blade** is a one-on-one fighting game where you control a skilled samurai (Kensei) battling against an intelligent AI opponent (Ronin). The game emphasizes timing, precision, and strategic use of attacks, blocks, and special moves.

The visual style is inspired by traditional Japanese woodblock art — featuring moonlit skies, mountain silhouettes, and dynamic ink splatter effects during combat.

---

##   Controls (Player — Kensei)

| Key | Action |
|-----|--------|
| A / D | Move left / right |
| W | Jump |
| J | Light Attack (fast, low damage) |
| K | Heavy Attack (slow, high damage) |
| L | Block (reduces damage by ~85%) |
| J + K | **ISSEN Special Move** (requires 3 pips) |

---

##   AI System (Ronin)

The enemy AI dynamically adapts based on its health:

- High HP → Defensive and calculated
- Low HP → Aggressive and reckless
- Capabilities:
  - Blocking incoming attacks
  - Jumping to evade
  - Performing its own **Shadow Cut** special move

This creates an evolving fight rather than predictable patterns.

---

##   Core Features

###   Combat System
- Light and heavy attack mechanics
- Combo chaining with hit detection
- Block system with damage reduction
- Special move system powered by energy (pips)

###   Visual Effects
- Dynamic slash trails
- Hit particles on impact
- Ink splatter effects on the ground
- Cinematic camera shake on damage

###   HUD Elements
- Health bars for both fighters
- Combo counter
- Special energy (pip system)
- 60-second round timer

###  Game Flow
- Real-time duel mechanics
- Win/Loss detection
- End screen with rematch option

---

##   Mechanics Breakdown

### Special Move System
- Each successful hit builds special energy
- 3 pips required to execute **ISSEN**
- High-risk, high-reward finisher

### Blocking
- Reduces incoming damage by ~85%
- Requires timing — holding block blindly limits offense

### AI Difficulty Curve
- Adaptive aggression ensures replayability
- Forces player to adjust strategy mid-fight

---

##   Tech Stack

- **HTML5 Canvas** — rendering and animations
- **JavaScript** — game logic, physics, AI behavior
- **CSS** — UI styling and layout

---

##  How to Run

1. Download or clone the project
2. Open `index.html` in your browser  
   *(No build tools or dependencies required)*

---

##   Future Improvements

- Multiplayer (local or online)
- Sound design (sword clashes, ambient audio)
- More characters with unique abilities
- Advanced combo system
- Mobile controls support

---

##   Final Note

This project is not just a game — it’s a study in **real-time combat systems, animation feedback, and player-AI interaction**.

If you’re building games, pay attention to:
- Feedback loops (visual + mechanical)
- Input responsiveness
- AI unpredictability

That’s where good games become addictive.

---
