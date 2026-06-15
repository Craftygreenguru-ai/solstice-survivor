# This is a submission for the June Solstice Game Jam 2026*

---

## What I Built

**Solstice Survivor** is a Vampire Survivors-style horde game where you are the **Light Bearer** — the last guardian of the summer solstice.

As shadow creatures surge at the peak of June 21, you wield sunbeams to hold back the darkness, collect Pride power orbs to boost your abilities, and click golden freedom chains to liberate imprisoned spirit allies. Survive 10 minutes and the solstice is restored.

The game connects to every major June celebration:
- 🌞 **June Solstice** — the entire game is a 10-minute metaphor for the longest day. The sky shifts from dawn to peak sun as you progress. When you die, the light goes out.
- 🏳️‍🌈 **Pride** — rainbow orbs are your primary power-up system. The Light Bearer is surrounded by a Pride spectrum shield. Color = power.
- ✊ **Juneteenth** — the freedom chain mechanic is a direct homage to June 19, 1865. Spirit allies are imprisoned on the map; you must actively break their chains to free them. They then fight alongside you — freedom as a force multiplier.
- ☀️ **Light vs Darkness** — the most primal solstice theme. You are light. Everything coming for you is shadow.

---

## Video Demo

<!-- [Embed or link your gameplay recording here] -->

*Recommended: record a 2-minute run showing the opening wave, a chain-break liberation, collecting Pride orbs, and surviving to at least wave 3.*

---

## Code

{% github YOUR_USERNAME/solstice-survivor %}

**Live demo:** [YOUR_GITHUB_PAGES_URL]

---

## How I Built It

### Architecture

Built on React 18 + Vite, with the game engine running on HTML5 Canvas layered inside React's component tree. React handles the UI overlays (HUD, menus, wave notifications) while Canvas handles all real-time game rendering — enemy movement, projectile physics, particle effects, and collision detection.

### The Survival Mechanic

The 10-minute timer is the solstice arc. Each minute = roughly one hour of the actual solstice day (6am to 4pm). The background sky gradient updates in real time. At the 5-minute mark (solar noon), enemies hit peak difficulty — this is the solstice's turning point, and it's also when the game is hardest.

### The Freedom Chain System

Freedom chains are the game's Juneteenth mechanic. Chained spirit allies are placed throughout the map — they glow gold and pulse. When you reach one and break the chain (right-click or E), the spirit is liberated and begins fighting alongside you. This scales — later in the game, a ring of freed spirits creates a formidable defensive formation. Freedom, literally, compounds.

### Pride Power System

Six Pride orbs cycle through the visible light spectrum (ROYGBV):
- 🔴 Red: damage boost
- 🟠 Orange: fire rate
- 🟡 Yellow: area of effect
- 🟢 Green: health regen
- 🔵 Blue: movement speed
- 🟣 Violet: spirit ally buff

Each orb lasts 15 seconds. Stacking orbs creates combination effects.

### Enemy Design

Shadow creatures spawn in escalating wave patterns. Early waves are slow pinwheels. Later waves introduce faster shadow darts and heavy shadow titans. The visual design uses inverted light — enemies are dark voids with faint inverse halos, making the contrast with your light-based character immediate and readable.

---

## Prize Category

*(Optional — include if submitting to Best Ode to Alan Turing or Best Google AI Usage)*

---

*Thanks for participating! — McSherry*
