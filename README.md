# Engineering Hamiltonians through Nonlinearities

Following the formalism described in "Black-box superconducting circuit
quantization" http://arxiv.org/abs/1204.0587 we can expand `sin(a+b+...+h.c.)`
or `cos(a+b+...+h.c.)` or any other nonlinear `f(a+b+...+h.c.)` in order to
obtain non-linear terms in the Hamiltonian (a, b, and other letters represent
the annihilation operators of various oscillator modes). If we drive some of
the modes classically we can create any non-linear term in the effective
Hamiltonian.

This module helps solve the constraint on the frequencies of the
modes (both the requirement that some of the monomials in the expansion are
resonant and that all the other terms in the expansion of the nonlinearity are
off-resonant).

