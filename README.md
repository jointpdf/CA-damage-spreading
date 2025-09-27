#Searching for complexity in cellular automata

Giordano Colombo, Andrea Del Torchio
July 16, 2024
Abstract
The study of damage spreading in cellular automata (CA) is essential for under-
standing chaos and phase transitions in CA and complex systems in general.
Using the concept of the Boolean derivative the damage spreading for one-
dimensional elementary cellular automaton is studied, defining the Lyapunov ex-
ponents that allow for the study of Lyapunov spectra of ECA. The spectra found
for II class rules 26, 108, and 127 are compatible with theoretical expectations.

1. Introduction
Cellular automata can be described as artificial programmable ”universes”, which are discreet in time
and space. The physics of these logical universes is deterministic and local. Local means that the state
of a cell at time t + 1 is only a function of its state and the states of the cells in a certain neighborhood
at time t. Deterministic means that once a local physics and an initial state of a cellular automaton
has been chosen, its future evolution is uniquely determined.
The most interesting cellular automata, balancing chaoticity and tendency to generate structures,
show complex behavior that cannot be easily predicted [1]. How to define complexity is not a trivial
question. Which universal features are shared by apparently different complex systems? The behavior
of physical systems close to critical points may answer this question. It is well known, from the theory
of phase transitions, that a given system (possibly made of many subsystems) can undergo strong
qualitative changes in its macroscopic properties if a suitable control parameter is adequately tuned.
Close to these critical points, some key characteristic constants (the so-called critical exponents) are
the same for very different systems [2]. At critical points, fractal structures and complex dynamical
patterns appear spontaneously. Observing such properties in those systems that are called ”complex,”
one can conjecture that complexity tends to appear close to instability points.
The study of perturbation or defects spreading in cellular automata, is essential for understanding
when these systems show complex behavior. It also helps us to understand the dynamics and emergent
properties of complex systems in general.
In this paper an analysis of damage spreading in cellular automata is proposed. It is made use of
the boolean derivative which allows us to compute the Lyapunov spectra of cellular automata. This
approach parallels the well-established method used in continuous-state dynamical systems, facilitating
the application of established theorems from dynamical systems theory.
