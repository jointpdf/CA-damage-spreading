# Searching for complexity in cellular automata

Giordano Colombo, Andrea Del Torchio --- july 16 2024

## Abstract
The study of damage spreading in cellular automata (CA) is essential for under-
standing chaos and phase transitions in CA and complex systems in general.
Using the concept of the Boolean derivative the damage spreading for one-
dimensional elementary cellular automaton is studied, defining the Lyapunov ex-
ponents that allow for the study of Lyapunov spectra of ECA. The spectra found
for II class rules 26, 108, and 127 are compatible with theoretical expectations.

## Introduction
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

## Conclusion
The Lyapunov spectra found for the examined rules behave as expected. Even though the connection
between Lyapunov exponents as earlier defined and the evolution in the configuration space of the
system is not straightforward, one expects class II automata to have a high fraction of its Lyapunov
exponents to be −∞, indicating that a random mutation of a cell is likely to die out quickly. This
is found to be the case. Analyzing closer the spectrum of rule 108, it can be seen how it presents a
7peak around the value 0. This can be interpreted by observing the characteristic ”streams” of rule
108, which once created remain present for every successive time t. It can be seen then how a random
mutation might not die out, but also wouldn’t spread, remaining localized. This is equivalent to a 0
Lyapunov exponent. Lastly, the analyzed rules present a narrow peak around some (low) values of
their spectra, indicating a local chaoticity. This is to be compared to the spectra of class III and IV,
which present less (or none) stable exponents and a wider distribution centered around higher values
of Lyapunov exponents [5]

## References
[1] Stephen Wolfram. Universality and complexity in cellular automata. Physica D: Nonlinear Phe-
nomena, 10(1-2):1–35, 1984.  
[2] James J Binney, Nigel J Dowrick, Anthony J Fisher, and Mark EJ Newman. The theory of critical
phenomena: an introduction to the renormalization group. Oxford University Press, 1992.  
[3] Milan Vispoel, Aisling J Daly, and Jan M Baetens. Damage spreading and the lyapunov spectrum
of cellular automata and boolean networks. Chaos, Solitons & Fractals, 184:114989, 2024.  
[4] Gérard Y Vichniac. Boolean derivatives on cellular automata. Physica D: Nonlinear Phenomena,
45(1-3):63–74, 1990.  
[5] Baetens J. M. Vispoel M., Daly A. J. Damage spreading and the lyapunov spectrum of cellular
automata and boolean networks. Chaos, Solitons & Fractals, 184, 114989, 2024.  
[6] Franco Bagnoli, R Rechtman, and Stefano Ruffo. Damage spreading and lyapunov exponents in
cellular automata. Physics Letters A, 172(1-2):34–38, 1992.  
[7] S Wolfram. A new kind of science (wolfram media, inc., champaign il, usa). 2002.  
[8] Wentian Li, Norman Packard, et al. The structure of the elementary cellular automata rule space.  
Complex systems, 4(3):281–297, 1990.  
