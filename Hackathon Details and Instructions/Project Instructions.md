# Project Instructions
Below, we've listed the options for this year's hackathon. Instead of keeping it completely open like last year, we've provided two main tracks/topics with challenges for three ability levels. Select a project that matches your group's experience and that you will learn something from.

All projects must use Qiskit! For each project, we’ve listed a few resources that should help you get started. We encourage you to explore aspects of the topic that interest you (even if you end up modifying the project slightly), and demonstrate your code on simulators or real (free) machines when viable. We’ve also provided additional challenges, which may not be viable as hackathon projects (although you're welcome to give them a shot) but could be interesting to learn about or if you’d like to keep learning afterward.

Good luck to everyone, and we're excited to see your projects!

## Option 1: Quantum Errors
### Beginner
Implement the simple bit flip error-correcting code explained in section 2 [here](https://www2.physics.ox.ac.uk/sites/default/files/ErrorCorrectionSteane06.pdf) and demonstrate the effect of the code for various errors, including superposition states. You may find it useful to break your circuit into multiple parts and use some classical logic in between, using a state vector simulator to maintain your quantum state. Alternatively, you may be able to do this all in one circuit, with operations found in [qiskit.circuit.classical](https://qiskit.org/documentation/apidoc/circuit_classical.html).
### Intermediate
Implement an error mitigation or error suppression technique of your choice, and analyze its performance using randomized benchmarking. Check out [this page](https://research.ibm.com/blog/quantum-error-suppression-mitigation-correction) to learn a bit about types of error suppression and mitigation, and [this one](https://learn.qiskit.org/course/quantum-hardware/measurement-error-mitigation) to learn about how some techniques can be implemented.
### Advanced
Use Qiskit Pulse to explore pulse sequences and their effect on coherence time and overall circuit fidelity. You could choose to consider any selection of factors, like different methods, hardwares, circuit depth, or something else. Check out [this page](https://qiskit.org/learn/course/quantum-hardware-pulses) to learn how to use Qiskit Pulse.
### Learn More
Look into [scalable LDPC codes](https://journals.aps.org/prxquantum/abstract/10.1103/PRXQuantum.2.040101) or [state distillation methods](https://en.wikipedia.org/wiki/Magic_state_distillation) as alternatives to surface codes.
## Option 2: Quantum Simulation
### Beginner
Prepare and demonstrate states that will not change (or will be multiplied by an overall constant) when certain single and 2-qubit gates of your choice are applied. You may also do this for a series of gates. These are called eigenstates of whatever operation is being applied and are extremely useful in predicting the behavior of quantum systems. If you know how to find these analytically, take this further by proposing how it might be useful in modeling physical phenomena and possibly implementing a toy model of some process. Learn a little about these states, which are called eigenvectors or eigenstates, [in this reference](https://mathforquantum.quantumtinkerer.tudelft.nl/6_eigenvectors_QM/) (they refer to operators, these are your circuits or sequences of gates).
### Intermediate
Use a variational optimization method like VQE to find the ground state energy of a simple molecule of your choice (typically, H2 or LiH). [This page](https://qiskit.org/learn/course/algorithm-design) is a good place to get started. 
### Advanced
Implement trotterization to simulate a basic physical system, like the Hubbard model or a molecular Hamiltonian. Read a little about this [here](https://www.nature.com/articles/s41467-021-25196-0), [here](https://vtomole.com/blog/2019/04/07/trotter), and [here](https://learn.microsoft.com/en-us/azure/quantum/user-guide/libraries/chemistry/concepts/algorithms), but note that these sources may be tricky to follow without some quantum mechanics background. 
