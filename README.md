 Critters Project — Custom Behavior Programs

This repository contains my custom critter instruction files designed for the Critter Simulation Project 🪶.
Each critter’s behavior was carefully crafted through conditional logic, register usage, and strategic movement patterns to simulate decision-making, survival, and adaptation.



 Included Critters

Wall Critter

A defensive, sentinel-style critter that reacts to its surroundings:
	•	Detects enemies, walls, and empty spaces with fine-tuned conditional checks (ifenemy, ifwall, ifempty).
	•	Uses movement logic and right-turn sequences to create dynamic perimeter behavior.
	•	Writes and reads registers (r1, r2) for decision tracking and state comparison.
	•	Infects nearby opponents and maintains territory with adaptive control flow.

 Smart Fly Trap (ADB)

An intelligent offensive critter focused on awareness and coordination:
	• Constantly scans all 8 directions for allies and enemies using ifally and ifenemy.
	• Balances hunger and aggression through ifstarving and eat logic.
	• Avoids friendly fire using team-aware infection rules.
	• Employs branching logic (go, write, ifeq, ifgt) for self-modifying decision-making.
	• Infects strategically while maintaining spatial control and formation.


Note on Code Availability

I also developed the Java-based behavioral logic that powers these critters (including movement, combat, and state overrides).
However, due to academic policy restrictions, the Java compiler and framework files (e.g., Critter.java, Main.java, etc.) cannot be included in this repository.
This repo therefore contains only the custom .txt instruction programs that define critter behavior.



Tech Context
	•	Critter assembly-like language syntax
	•	Register-based decision logic (r1, r2, r10)
	•	Pattern-based control flow
	•	Complex multi-conditional AI-style behavior

⸻

💡 These critters represent an intersection of algorithmic thinking, systems design, and creative strategy — a fun challenge in emergent behavior programming.
