TL;DR:
This repository contains my custom Critter Simulation programs featuring two unique designs: Wall, a defensive sentinel, and Smart Fly Trap (ADB), an adaptive hunter. Both use conditional logic, registers, and strategic movement patterns to simulate intelligence and coordination. The Java framework is excluded due to academic policy.

⸻

Critters Project – Custom Behavior Programs

This repository contains my custom critter instruction files created for the Critter Simulation Project. Each critter’s behavior was designed through conditional logic, register usage, and strategic movement patterns to simulate decision-making, survival, and adaptation.

Included Critters

Wall Critter
A defensive, sentinel-style critter that reacts to its surroundings. It detects enemies, walls, and empty spaces using conditional checks (ifenemy, ifwall, ifempty). It uses movement logic and right-turn sequences for perimeter control, writes and reads registers (r1, r2) for tracking decisions, and infects nearby opponents to maintain territory.

Smart Fly Trap (ADB)
An intelligent offensive critter focused on awareness and coordination. It scans all eight directions for allies and enemies (ifally, ifenemy), balances hunger and aggression (ifstarving, eat), avoids friendly fire, and uses branching logic (go, write, ifeq, ifgt) for adaptive decision-making. It infects strategically while maintaining spatial awareness and formation.

Note on Code Availability
I also developed the Java-based behavioral logic that powers these critters, including movement, combat, and state overrides. However, due to academic policy restrictions, the Java compiler and framework files (such as Critter.java and Main.java) cannot be included here. This repository contains only the custom .txt instruction programs that define critter behavior.

Tech Context
	•	Critter assembly-style language syntax
	•	Register-based decision logic (r1, r2, r10)
	•	Pattern-based control flow
	•	Multi-conditional AI-style behavior

These critters combine algorithmic thinking, systems design, and creative strategy—a fun challenge in emergent behavior programming.
