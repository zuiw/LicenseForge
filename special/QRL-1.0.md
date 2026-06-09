# Quantum-Resistant License, Version 1.0 (QRL-1.0)

**Copyright (C) 2026 [Your Name or Organization]**

A license that requires the use of post-quantum cryptography and quantum-resistant
algorithms.

## Preamble

The QRL addresses the emerging threat of quantum computing to current
cryptographic standards.  As quantum computers advance, many widely-used
encryption algorithms (RSA, ECC, ECDSA) will become vulnerable.  This
license requires that software using cryptographic operations must support
or be compatible with post-quantum cryptographic algorithms standardized by
NIST or equivalent bodies.

## TERMS AND CONDITIONS

### 0. Definitions.

"This License" refers to version 1.0 of the Quantum-Resistant License
(QRL-1.0).

"The Software" means the cryptographic software, library, protocol, or
system licensed under this License.

"Post-Quantum Cryptography" means cryptographic algorithms that are
believed to be secure against attack by quantum computers, as standardized
by NIST or an equivalent standards body.

"Classical Cryptography" means traditional cryptographic algorithms that
are not believed to be secure against quantum computer attack.

"Security-Sensitive Operation" means any cryptographic operation used for
authentication, encryption, key exchange, digital signatures, or similar
security functions.

### 1. Permissions.

You may use, copy, modify, and distribute the Software for any lawful
purpose, subject to the quantum-resistance conditions below.

### 2. Post-Quantum Requirement.

If the Software performs Security-Sensitive Operations, you must:
- **a)** Support at least one Post-Quantum Cryptography algorithm for each
  Security-Sensitive Operation;
- **b)** Default to Post-Quantum Cryptography where feasible;
- **c)** Document which Post-Quantum algorithms are supported.

### 3. Hybrid Mode.

During the transition period, the Software may support a hybrid mode that
uses both Classical Cryptography and Post-Quantum Cryptography
simultaneously, provided that:
- The Post-Quantum algorithm is the primary mode;
- The Classical algorithm is clearly marked as a fallback;
- Users are warned if they choose to use Classical-only mode.

### 4. Algorithm Agility.

The Software must be designed to allow cryptographic algorithm replacement
without breaking existing functionality or data formats.

### 5. Disclosure.

You must:
- **a)** Disclose which cryptographic algorithms the Software uses;
- **b)** Indicate which are Post-Quantum and which are Classical;
- **c)** Document the quantum-security level of each algorithm.

### 6. Termination.

Failure to implement Post-Quantum Cryptography for Security-Sensitive
Operations terminates rights.  A 180-day cure period applies to allow
upgrades.

### 7. Disclaimer of Warranty.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF QUANTUM RESISTANCE.

### 8. Limitation of Liability.

IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR QUANTUM COMPUTING BREACHES.

**END OF TERMS AND CONDITIONS**


## How to Apply These Terms

Include the following notice:

```
<Software name>
Copyright (C) <year> <author>
Licensed under the Quantum-Resistant License, version 1.0 (QRL-1.0).
Post-quantum cryptography required for security operations.
Full terms: <URL>.
```
