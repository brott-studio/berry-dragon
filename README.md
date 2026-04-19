# Berry Dragon's Appetite — Paper Prototype

A 10-minute solo puzzle/tactics prototype. Single HTML file, no dependencies.

## Play
Double-click `index.html` (or drag it into a browser tab). No build, no install.

## Goal
Grab the **Chalice Key** from the **Golden Maze** and reach **Treasure Mountain** before the Dragon wakes.

## Rules
- Click any **highlighted (orange-bordered)** zone adjacent to you to move there.
- Every move: **Hunger +1**. If hunger hits **10**, the Dragon wakes → you lose.
- **Dragonberries** zone: gain 2 berries.
- **Feed Dragon** button: spend 1 berry to reduce hunger by 1.
- **Golden Maze**: entering grants the Chalice Key 🗝️.
- **Treasure Mountain**: with the Key in hand → you win.

## Zone effects
| Zone | Effect |
|---|---|
| 🏝️ Vacation Island | Safe start |
| 🌊 Sea of Wave | Transit |
| 🌲 Fantastic Forest | Random event (berry / calm / -1 hunger) |
| 🌫️ Fog of Misdirection | Teleports you to a random neighbor |
| 🫐 Dragonberries | +2 berries |
| 🏜️ Deserted Desert | Hunger +1 extra |
| 🕳️ Quicksand Pool | Hunger +1 extra |
| 🌀 Golden Maze | Grants Chalice Key |
| 🐉 Berry Dragon | Hunger +2 extra (risky shortcut) |
| ⛰️ Treasure Mountain | Win if you hold the Key |

## Typical play
- **Fastest win path** (Vacation → Sea → Forest → Fog → Maze → Mountain): 5 moves, ~5 hunger — easy win if Fog doesn't scramble you badly.
- **Safer path** through Berries first adds 2–3 turns but builds a feeding buffer.
- Expect 6–8 turns in a typical playthrough.
