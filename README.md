# quantum-reinforcement-learning
This repository was created for the final project of CS 394R: Reinforcement Learning taken at UT, Austin by Jordi Ramos and Benjamin Pachev. 

The goal of our project was to replicate the results of a paper titled "Quantum Reinforcement Learning" (Dong et al., 2008).

Presentation slides: https://docs.google.com/presentation/d/1abrlKgSeyTP_ORuia_wSIjcEFQtxFqfgNg6KOaM4OvM/edit?usp=sharing.
Presentation video link: https://youtu.be/RB9SSw_-shY

The reposistory contains three Jupyter notebooks documenting our work.

## SARSA
This shows our work in replicating the baseline TD(0) algorithm mentioned in the original paper. We have implemented the Gridworld ourselves, as well as the SARSA algorithm.
## QRL
This shows our work in replicating the QRL algorithm from the original paper by Dong et al. (2008), and the results.
## Grover's Algorithm Using Qiskit
This shows our attempt in trying to run the Grover's algorithm on a real quantum computer. We have succesfully implemented the quantum gates for the Grover's algorithm. All we need to do next is to schedule a job on a real quantum computer and anaylze the results. Our original plan is to run QRL on a real quantum computer, but found out that it is not yet possible. See our report for details.

Each notebook is completely self-contained.

We have also included our presentation slides in a pdf format.

References:
1. Dong, D., Chen, C., Li, H., and Tarn, T.-J. (2008).
Quantum reinforcement learning. IEEE Transactions on Systems, Man,
and Cybernetics, Part B (Cybernetics), 38(5):1207–1220.
