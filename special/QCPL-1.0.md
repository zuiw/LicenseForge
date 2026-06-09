# Quantum Computing License, Version 1.0 (QCPL-1.0)

**Copyright (C) 2026 [Your Name or Organization]**

A license for quantum computing software requiring algorithm verification, hardware-independent implementation, and quantum advantage disclosure.

## Preamble

The QCPL addresses the emerging field of quantum computing software. It requires that quantum algorithms be verifiable, implementations target hardware-independent abstractions where feasible, and claims of quantum advantage be substantiated. It promotes reproducible and trustworthy quantum software.

## TERMS AND CONDITIONS

### 0. Definitions.

"This License" refers to version 1.0 of the Quantum Computing License (QCPL-1.0).

"The Software" means the quantum algorithm, circuit, simulator, or quantum-classical hybrid system licensed under this License.

"Quantum Algorithm" means a sequence of quantum operations designed to solve a computational problem.

"Quantum Advantage" means a claimed computational speedup or capability improvement over classical alternatives.

"Hardware-Independent" means implementable on multiple quantum computing architectures (superconducting, trapped ion, photonic, etc.).

### 1. Permissions.

You may use, copy, modify, and distribute the Software, subject to the quantum computing conditions below.

### 2. Algorithm Verification.

Quantum Algorithms distributed under this License must include:
- **a)** A classical description of the intended computation;
- **b)** Proof of correctness for the algorithm;
- **c)** Error bounds and noise tolerance analysis;
- **d)** Validation results on simulators or hardware.

### 3. Hardware Independence.

The Software should target Hardware-Independent abstractions where possible:
- **a)** Use standard quantum gates and operations;
- **b)** Document architecture-specific optimizations;
- **c)** Support at least one open quantum assembly format (e.g., QASM);
- **d)** Provide simulator backends for testing.

### 4. Quantum Advantage Disclosure.

If you claim Quantum Advantage from the Software, you must:
- **a)** Specify the classical baseline being compared against;
- **b)** Provide benchmarking methodology and results;
- **c)** Disclose all assumptions and constraints;
- **d)** Make benchmarking code and data available.

### 5. Error Mitigation.

The Software must document:
- **a)** Error mitigation techniques used;
- **b)** Expected error rates and fidelity;
- **c)** Scalability limits of error correction;
- **d)** Validation methodology for results.

### 6. Termination.

Distributing quantum software with unsubstantiated Quantum Advantage claims or without verification documentation terminates rights. A 90-day cure period applies.

### 7. Disclaimer of Warranty.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF QUANTUM SPEEDUP OR CORRECTNESS.

### 8. Limitation of Liability.

IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR QUANTUM COMPUTING CLAIMS.

**END OF TERMS AND CONDITIONS**
