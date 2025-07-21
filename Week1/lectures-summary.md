# Week 1 - Lecture Summary (Power Electronics, NPTEL IISc)

## Lecture 1: Getting started with NgSpice
- Introduction to circuit simulation using NgSpice.
- Explained what a `.cir` file is and how to write a basic netlist.
- Ran a simple resistor-capacitor (RC) circuit simulation.

## Lecture 2: Refactoring the .cir
- Techniques for cleaning and organizing `.cir` files.
- Added comments, reused code, and modularized the file for easier updates.

## Lecture 3: Sub-circuits
- Concept of sub-circuits using `.subckt` and `.ends` syntax.
- Helped reuse parts of circuits (e.g. an op-amp model).
- Nested sub-circuits explained.

## Lecture 4: gschem and netlist generation
- Introduction to graphical circuit design using gschem.
- Showed how to create circuits visually and generate a netlist.
- Connected gschem with NgSpice.

## Lecture 5: Setting up for simulation with Octave
- Explained use of GNU Octave for simulating equations.
- Installed Octave and basic setup steps.
- Imported NgSpice output data into Octave.

## Lecture 6: Getting started with equation based simulation
- Simulated circuits purely with equations using Octave.
- Compared simulation results between Octave and NgSpice.
- Useful when spice-based simulation is not suitable.

## Lecture 7: Resuming a simulation in Octave
- Showed how to pause and resume simulations.
- Save and load workspace and data for continuing work.
