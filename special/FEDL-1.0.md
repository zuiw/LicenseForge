# Federated Learning License, Version 1.0 (FEDL-1.0)

**Copyright (C) 2026 [Your Name or Organization]**

A license for federated learning frameworks requiring gradient privacy, model aggregation transparency, and client data sovereignty.

## Preamble

The FEDL governs federated learning platforms where models are trained across decentralized devices without centralizing raw data. It requires disclosure of aggregation algorithms, differential privacy guarantees, client selection fairness, and prohibits reconstruction of individual training data from model updates.

## TERMS AND CONDITIONS

### 0. Definitions.

"Federated Learning" means a machine learning technique where models are trained across decentralized data without centralizing raw data.

"Client Data" means data held by each participant in a Federated Learning system.

### 1. Permissions.

You may use, copy, modify, and distribute the Software, subject to the federated learning conditions below.

### 2. Aggregation Transparency.

The aggregation algorithm, including any weighting, selection, and compression methods, must be documented.

### 3. Privacy Guarantees.

Differential privacy parameters (epsilon, delta) or other formal privacy guarantees must be disclosed per training round.

### 4. Client Sovereignty.

Client Data must never leave the client device without explicit consent. Model updates must be minimized to training parameters only.

### 5. Anti-Reconstruction.

The Software must implement protections against reconstruction of Client Data from model updates.

### 6. Termination.

Violating client data sovereignty or failing to disclose aggregation methods terminates rights. A 60-day cure period applies.

### 7. Disclaimer of Warranty. Limitation of Liability.

THE SOFTWARE IS PROVIDED "AS IS". IN NO EVENT SHALL THE AUTHORS BE LIABLE.

**END OF TERMS AND CONDITIONS**
