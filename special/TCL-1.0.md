# Trusted Compute License, Version 1.0 (TCL-1.0)

**Copyright (C) 2026 [Your Name or Organization]**

A license for trusted execution environments requiring attestation, secure
enclaves, and verifiable computation.

## Preamble

The TCL is for software running in trusted execution environments (TEEs),
secure enclaves, and confidential computing platforms.  It requires
hardware attestation, secure provisioning, and verifiable computation so
that users can cryptographically verify the integrity of the computation.

## TERMS AND CONDITIONS

### 0. Definitions.

"This License" refers to version 1.0 of the Trusted Compute License
(TCL-1.0).

"The Software" means the trusted compute application licensed under this
License.

"Attestation" means cryptographic evidence that the Software is running in
a genuine trusted execution environment.

"Secure Enclave" means a hardware-isolated execution environment that
protects code and data from the host system.

### 1. Permissions.

You may use, copy, modify, and distribute the Software for any lawful
purpose, subject to the trusted compute conditions below.

### 2. Attestation.

The Software must support remote Attestation, allowing users to verify:
- **a)** The integrity of the Secure Enclave;
- **b)** The exact code version running;
- **c)** The configuration and security settings.

### 3. Secure Provisioning.

Secrets and keys must be provisioned securely, with:
- **a)** Encryption during provisioning;
- **b)** Binding to the specific enclave identity;
- **c)** Revocation capability if compromised.

### 4. Verifiable Computation.

Where feasible, the Software should support verifiable computation so that
results can be independently verified without re-execution.

### 5. Transparency.

You must document:
- The TEE hardware and security model;
- The Attestation verification process;
- Known limitations and attack surfaces.

### 6. Termination.

Distribution without Attestation support terminates rights.
A 90-day cure period applies.

### 7. Disclaimer of Warranty.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF COMPUTE SECURITY.

### 8. Limitation of Liability.

IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR ENCLAVE BREACHES.

**END OF TERMS AND CONDITIONS**
