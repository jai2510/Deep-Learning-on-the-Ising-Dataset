# Deep Learning on the Isling Dataset

In this notebook, we show how one can use deep neural nets to classify the states of the 2D Ising model according to their phase.
The Hamiltonian for the classical Ising model is given by

𝐻=−𝐽 ∑ ⟨𝑖𝑗⟩𝑆𝑖𝑆𝑗 ,

where the lattice site indices i,j run over all nearest neighbors of a 2D square lattice, and J is some arbitrary interaction energy scale. We adopt periodic boundary conditions. Onsager proved that this model undergoes a phase transition in the thermodynamic limit from an ordered ferromagnet with all spins aligned to a disordered phase at the critical temperature T_c. For any finite system size, this critical point is expanded to a critical region around T_c.

