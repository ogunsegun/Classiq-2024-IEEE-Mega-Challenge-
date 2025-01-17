# Classiq-2024-IEEE-Mega-Challenge-
Variational Quantum Algorithms (VQAs) have gained attention as promising methods for realizing quantum advantage on Noise Intermediate-Scale Quantum (NISQ) devices. These algorithms consist of fine-tuned parameterized operations to optimize an objective function.

Their flexibility and ability to function without error correction techniques make them
particularly well-suited to the capabilities of current quantum computing technology.
An important part of building a good VQA for specific applications is to correctly tailor the
variational ansatz, which can include symmetries or conserved quantities that reflect on the
applications' outputs.
In the context of constructing ansatzes for specific applications, the work Symmetry enhanced
variational quantum spin eigensolver by Chufan Lyu et al. presents an ansatz specifically tailored
to spin systems with conserved total spin number using the Variational Quantum Eigensolver
(VQE).

**Detailed Challenge Description**
In this challenge, your goal is to reproduce the results obtained in the paper for N=4 qubits.
You should apply both the Sz-conserving ansatz, and hardware efficient ansatzes between 5 and
15 layers. A good solution to this challenge is considered to be composed of estimates of the
ground state energy of this system as well as an analysis of the behavior of the algorithm
when varying the initial parameters.
