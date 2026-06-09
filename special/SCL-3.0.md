# Secure Communications License, Version 3.0 (SCL-3.0)

**Copyright (C) 2026 [Your Name or Organization]**

A license for communications software requiring end-to-end encryption,
forward secrecy, and metadata protection.

## Preamble

The SCL-3.0 addresses the security and privacy requirements of
communications software.  It requires end-to-end encryption by default,
forward secrecy, minimal metadata collection, and open security audits.

## TERMS AND CONDITIONS

### 0. Definitions.

"This License" refers to version 3.0 of the Secure Communications License
(SCL-3.0).

"The Software" means the communications software licensed under this
License.

"End-to-End Encryption" means encryption that ensures only the
communicating parties can read the messages.

"Forward Secrecy" means that compromise of long-term keys does not
compromise past session keys.

"Metadata" means data about communications such as sender, recipient,
timestamps, and message size.

### 1. Permissions.

You may use, copy, modify, and distribute the Software for any lawful
purpose, subject to the secure communications conditions below.

### 2. End-to-End Encryption.

The Software must implement End-to-End Encryption by default for all
private communications.  The encryption implementation must:
- **a)** Use well-vetted cryptographic libraries;
- **b)** Protect against known attacks (replay, man-in-the-middle);
- **c)** Not include backdoors or exceptional access.

### 3. Forward Secrecy.

The Software must implement Forward Secrecy for all encrypted
communications.

### 4. Metadata Protection.

The Software must minimize Metadata collection to what is strictly
necessary for operation.  Metadata must be:
- Encrypted in transit and at rest;
- Retained only as long as necessary;
- Not shared with third parties without consent.

### 5. Open Audit.

The encryption implementation must be:
- **a)** Documented with a public specification;
- **b)** Subject to independent security audit;
- **c)** Reproducible from source code.

### 6. Termination.

Distribution without End-to-End Encryption terminates rights.
A 60-day cure period applies.

### 7. Disclaimer of Warranty.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF SECURITY.

### 8. Limitation of Liability.

IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR COMMUNICATION BREACHES.

**END OF TERMS AND CONDITIONS**
