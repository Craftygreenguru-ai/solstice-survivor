# ☀️ Solstice Survivor

> *"Survive the longest day. Wield sunbeams. Free the light."*

A horde-survival browser game for the **[June Solstice Game Jam 2026](https://dev.to/devteam/join-us-for-the-june-solstice-game-jam-2026)**

![June Solstice](https://img.shields.io/badge/June%20Solstice-Game%20Jam%202026-ffd700?style=for-the-badge)
![React](https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-Build-646CFF?style=for-the-badge&logo=vite&logoColor=white)

---

## 🎮 What Is This?

**Solstice Survivor** is a Vampire Survivors-style top-down horde game where you play as the **Light Bearer** — the last guardian of the summer solstice.

As darkness rises at the peak of June 21, you must:
- 🌞 Wield **sunbeams** to hold back waves of shadow creatures
- 🏳️‍🌈 Collect **Pride power orbs** to boost your abilities
- ⛓ Click **golden freedom chains** to liberate imprisoned spirit allies
- ✊ Answer **Juneteenth knowledge challenges** for bonus power
- ⏱ Survive **10 minutes** to restore the Solstice

---

## 🕹️ How to Play

**Open `index.html` via a local server (see below). No install required.**

### Desktop Controls
| Input | Action |
|-------|--------|
| WASD / Arrow Keys | Move |
| Left Click Hold | Aim & Shoot |
| Right Click / E | Break Nearby Chain |

### Mobile Controls
| Input | Action |
|-------|--------|
| Left Side Touch | Virtual Joystick (Move) |
| Right Side Hold | Aim & Shoot |
| Chain Button | Break Nearby Chain |

---

## 🏗️ How to Run

> ⚠️ This app uses ES modules — it must be served over HTTP, not opened as a file directly.

```bash
# Option 1: npx serve (recommended)
npx serve .

# Option 2: Python
python3 -m http.server 8080

# Option 3: VS Code Live Server extension
# Right-click index.html → Open with Live Server
```

Then visit `http://localhost:3000` (or whichever port).

---

## 📁 Repository Structure

```
solstice-survivor/
├── index.html                    # App entry point
├── logo.png                      # Game icon
├── README.md                     # This file
├── LICENSE                       # MIT License
├── SUBMISSION.md                 # DEV.to submission post
└── assets/
    ├── index-CtnJzDFt.js         # Compiled game bundle (React + game engine)
    └── index-WkDnYVCD.css        # Styles
```

---

## 🎨 Game Features

- **Dynamic sky** — background shifts from dawn to peak solstice as you progress
- **Wave system** — escalating enemy hordes every 60 seconds
- **XP & leveling** — collect gems, level up, unlock abilities
- **Pride orbs** — rainbow collectibles that grant temporary power boosts
- **Freedom chains** — golden chains scattered on the map; click to free spirit allies who fight alongside you
- **Mobile-first** — dual virtual joystick layout, fully playable on phone
- **High score tracking** — survive longer, score higher

---

## 🌍 Themes

| Theme | How it appears |
|-------|---------------|
| 🌞 June Solstice | 10-minute survival arc mirrors the longest day; sky changes with progress |
| 🏳️‍🌈 Pride | Rainbow orbs, Pride shield visual, color-coded power system |
| ✊ Juneteenth | Freedom chain mechanic — imprisoned spirits gaining their freedom |
| ☀️ Light vs Darkness | Core gameplay loop — you are light, enemies are shadow |

---

## 🛠️ Tech Stack

| What | How |
|------|-----|
| Framework | React 18 |
| Build | Vite |
| Rendering | HTML5 Canvas + DOM |
| Storage | localStorage |

---

## 📝 License

MIT — fork it, remix it, keep the solstice alive.

---

*Built for the June Solstice Game Jam 2026*
