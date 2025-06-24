# Star Wars Galactic Conquest

This is a simple browser-based strategy prototype inspired by the **Galactic Conquest** game mode from the Star Wars Battlefront series.  The project consists of a single HTML file that renders a grid of planetary systems.  Players manage fleets and resources while the AI opponent does the same.

## How to Play

1. Open `GalacticConquest.html` in a modern web browser.
2. When prompted, choose whether to play as the Republic or the CIS.  Your starting homeworld will be populated with an initial fleet.
3. The grid shows every planet as a clickable square:
   - **Green** indicates your starting world.
   - **Red** indicates systems under control of the Republic/Empire.
   - **Blue** indicates systems controlled by the Separatists/Rebels.
4. Select a system to view available actions.  Selecting a fleet shows options for moving or replenishing units.
5. Use the control buttons below the grid to perform actions each turn:
   - **End Turn** – Collect income from controlled planets and trigger the AI turn.
   - **Create Fleet** – Spend resources to raise a new fleet at the selected friendly system.
   - **Boost Economy** – Increase income on a controlled system.
   - **Garrison Units** – Move troops from a selected fleet into the planet’s garrison.
   - Forms are provided to replenish units or report losses for both player and AI forces.
6. Fleets may move to adjacent systems. Battles are resolved interactively via browser prompts asking who won and whether units were destroyed.
7. Continue playing turns until one faction controls the galaxy or you choose to end the session.

## Features

- **Interactive Map** – Over fifty Star Wars planets laid out on a square grid.
- **Resource Management** – Each controlled system provides income used to create fleets and reinforce troops.
- **Fleet and Garrison System** – Manage mobile fleets and planetary defenses separately.
- **Turn-Based AI** – An AI opponent gathers income, moves fleets, and attempts to conquer or blockade your worlds.
- **Manual Combat Resolution** – Battles and invasions are resolved via simple confirmation prompts, allowing the player to narrate outcomes.

This prototype can serve as a starting point for a more companion tool for campaigns.
