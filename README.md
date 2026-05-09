# quantum_simulations
Quantum simulation using quantum computing technology

Wavefucntion_evoloution: This is my implementation of the time evolution of the N=2 LMG Hamiltonian using PennyLane. I set up the full 4-qubit JW-transformed Hamiltonian and used the Trotter formula to approximate the time evolution over one full oscillation. I then compared the approximation to the exact analytical solution to see how close the two are. I also manually built the Trotter circuit and verified it matches PennyLane's built in TrotterProduct function.
