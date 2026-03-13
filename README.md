This collection features three distinct tactical combat simulators written in Python. Each game offers a unique take on grid-based strategy, ranging from fast-paced tank skirmishes to complex naval fleet maneuvers.

1. Pacific War 1 (The Flagship)
A sophisticated naval simulator focused on the "Information War," weather conditions, and long-term logistics.

Game Info
Classes: Carrier (C), Battleship (B), Cruiser (R), Destroyer (D), and Submarine (S).

Key Mechanics:

3-2-2 Repair Cycle: Ships unlock a 20 HP repair action by staying stationary for 3 turns, then every 2 turns thereafter (up to 75% max HP).

Class Movement: Destroyers move 3 tiles, Cruisers 2, and others move 1.

Advanced Intel: Uses radar "ghosts" (X, x, +, ?) to track last-known enemy positions and a Line-of-Sight (LOS) system that prevents shooting through islands.

Torpedoes: Delayed projectiles that travel across the map over several turns.

How to Play
M: Move (follow prompts for dX and dY).

F: Fire main batteries at specific coordinates.

A: Use Class Abilities (Air Recon, Sonar Ping, or Torpedo Launch).

R: Initiate Damage Control (if stationary requirements are met).

2. Tankgaem.py
A high-intensity tank combat game with destructible environments and multiple game modes.
+1

Game Info

Modes: 1v1, vs AI, Spectator, Training, and Line Battle (a large 20x20 scale war).
+1


Environment: The grid contains Walls (W) that can be destroyed and Rocks (R) that provide permanent cover.
+1


Damage System: Hits are randomized between Ricochets (1 dmg), Light/Heavy hits, and the rare Magazine Shot (20 dmg).
+1

How to Play

Move: Use W, A, S, D to move one tile at a time.
+1


Fire: Use F + Direction (e.g., fw, fa) to fire your shell in a straight line. Shells travel until they hit a tank, a rock, or a wall.
+1

3. Navalgaem
A tactical fleet command simulator that emphasizes ammo management and ship identification.
+1

Game Info

Ammo Types: Choose between AP (Armor Piercing) for standard damage or HE (High Explosive) for massive 18-damage strikes.
+2


Stealth: Submarines stay hidden unless they are very close or have recently fired, which increases their "reveal" (rev) timer.
+1


LOS: Ships cannot see or shoot through Islands (#).
+3

How to Play

Move: Use W, A, S, D to move. Ships move a set number of tiles based on their Speed (sp) stat.
+2


Fire AP (F): Deals 10 damage.
+1


Fire HE (G): Deals 18 damage.
+1


Targeting: If enemies are in range and visible, you will be prompted to select a target from a list.

🚀 Running the Games
Locally: Install Python and run python [fileName].py in your terminal.

Online: * Go to online-python.com.

Drag and Drop any of the three .py files into the editor.

Click Run.

⚖️ License
This collection is licensed under the Apache License 2.0. You are free to modify and distribute the code, provided you include the original license and copyright notice.
