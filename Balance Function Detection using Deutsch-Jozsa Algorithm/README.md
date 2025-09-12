# Balance Function Detection using Deutsch-Jozsa Algorithm

## Overview
- Implements the Deutsch-Jozsa quantum algorithm to detect if a function is constant or balanced for a 2-qubit case.
- Uses Qiskit for circuit construction, simulation, and analysis on a quantum simulator.
- Demonstrates quantum advantage over classical methods, with visualizations of circuit and results.

## Numerical Approach
- Circuit built with QuantumCircuit in Qiskit, including Hadamard and CNOT gates to simulate the oracle.
- Simulation performed using AerSimulator with transpilation and 1024 shots for statistical results.
- Results analyzed via measurement counts; visualization with histograms and circuit diagrams.
- Interpretation based on quantum interference: constant functions yield all |00⟩, balanced yield mixed states.

## Conclusion
- Successfully identifies the function as balanced based on equal-probability outcomes (|00⟩ ~510 counts, |11⟩ ~514 counts).
- Highlights deviations from standard algorithm (e.g., missing auxiliary qubit) but confirms core principles via interference.
- Provides a foundation for exploring general oracles and larger qubit systems in quantum computing.

See [Report.pdf](https://github.com/MinaShiri-Physics/Quantum-Computation-and-Information/blob/main/Balance%20Function%20Detection%20using%20Deutsch-Jozsa%20Algorithm/Report.pdf) for more details.
