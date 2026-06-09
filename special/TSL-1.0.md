# Trusted Source License, Version 1.0 (TSL-1.0)

**Copyright (C) 2026 [Your Name or Organization]**

A license requiring software supply chain security — dependency verification,
signed commits, and reproducible builds.

## Preamble

The TSL addresses software supply chain security.  It requires that all
dependencies be verified, that commits be signed, that builds be
reproducible, and that the software supply chain be transparent and
auditable.

## TERMS AND CONDITIONS

### 0. Definitions.

"This License" refers to version 1.0 of the Trusted Source License
(TSL-1.0).

"The Software" means the program licensed under this License.

"Supply Chain" means the chain of dependencies, tools, and processes used
to build and distribute the Software.

"Reproducible Build" means a build process that produces bit-for-bit
identical outputs from the same source.

### 1. Permissions.

You may use, copy, modify, and distribute the Software for any lawful
purpose, subject to the supply chain security conditions below.

### 2. Dependency Verification.

If you distribute the Software, you must:
- **a)** Maintain a software bill of materials;
- **b)** Verify checksums of all dependencies;
- **c)** Scan for known vulnerabilities;
- **d)** Document all direct and transitive dependencies.

### 3. Signed Commits.

All changes to the Software must be signed using a trusted cryptographic
key, with signatures verifiable through a public key infrastructure.

### 4. Reproducible Builds.

The Software must support Reproducible Builds, and you must document:
- **a)** The complete build environment;
- **b)** How to independently verify builds;
- **c)** Any non-reproducible components and why.

### 5. Vulnerability Disclosure.

You must maintain a mechanism for reporting security vulnerabilities,
with a published disclosure policy and expected response times.

### 6. Termination.

Distribution without a software bill of materials terminates rights.
A 90-day cure period applies.

### 7. Disclaimer of Warranty.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF SUPPLY CHAIN SECURITY.

### 8. Limitation of Liability.

IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR SUPPLY CHAIN ATTACKS.

**END OF TERMS AND CONDITIONS**
