# Electric-Circuit-Simulation

A browser-native, interactive electronic circuit simulator built from scratch using Modified Nodal Analysis (MNA).
# 🚀 Project Overview
This project aims to build a lightweight yet high-precision circuit simulation engine using the standard web stack. By leveraging the HTML5 Canvas API for schematic capture and Vanilla JavaScript for the numerical solver, this tool provides real-time visualization of electrical behavior without the need for external software or Java plugins.
The project follows a phased approach, starting with linear passive components (resistors, capacitors) and ideal sources, eventually expanding to complex nonlinear devices.

# 🛠 Core Tech Stack
HTML5 Canvas: Used for the interactive schematic editor, supporting component placement and real-time "moving yellow dots" to represent current flow.
CSS3: For a responsive UI, toolbar styling, and professional-grade oscilloscope-like data panels.
JavaScript (ES6+):
The Engine: A custom matrix solver implementing Modified Nodal Analysis (MNA) to handle both voltage and current constraints.
Numerical Methods: Employs LU Decomposition with Partial Pivoting for stable linear equation solving and Trapezoidal Rule integration for transient analysis.

# ✨ Key Features (Initial Phase)
Interactive Schematic Capture:
Drag-and-Drop: Native JS implementation for dragging components and wires over the canvas using hit-testing via context.isPointInPath.
Dynamic Editing: Right-click menus to modify component properties (e.g., resistance, voltage) on the fly.
Real-Time Simulation:
DC Operating Point: Solves for node voltages and branch currents in steady-state using MNA.
Transient Analysis: Provides a time-varying definition of voltage/current across any point in the circuit.
Virtual Oscilloscope: Integrated graphs showing time-domain waveforms for selected nodes or components.

# ⚙️ How it Works (Starting Logic)
Topological Mapping: The simulator uses Union-Find node detection to identify connections and map the physical circuit to a system matrix.
Matrix Assembly: For every node k, the engine writes a Kirchhoff’s Current Law (KCL) equation. It systematically builds the G (conductance) and B (voltage incidence) matrices to form the standard MNA equation: 
[ G  B^T ] [ V ] = [ V ]
[ B   0  ] [ I ]   [ I ]
Numerical Integration: To simulate capacitors and inductors, the engine uses Direct Discretization (Backward Euler or Trapezoidal Rule) to convert differential equations into solvable algebraic systems at every time step.

# 🗺 Roadmap
[x] Phase 1: Basic HTML/Canvas UI and linear DC solver (Resistors/Sources).
[ ] Phase 2: Implement Transient Analysis using the Trapezoidal Rule.
[ ] Phase 3: Nonlinear device support (Diodes/Transistors) using Newton-Raphson iteration.
[ ] Phase 4: Advanced stability features like Gmin Stepping and Source Stepping.
