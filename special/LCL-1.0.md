# Life-Critical License, Version 1.0 (LCL-1.0)

**Copyright (C) 2026 [Your Name or Organization]**

A license for life-critical systems requiring formal verification,
redundancy, and fail-operational design.

## Preamble

The LCL is for software used in life-critical systems — medical life
support, aviation flight control, nuclear safety, and autonomous braking.
Such systems require the highest levels of assurance: formal methods,
redundancy, fail-operational design, and certification.

## TERMS AND CONDITIONS

### 0. Definitions.

"This License" refers to version 1.0 of the Life-Critical License
(LCL-1.0).

"The Software" means the life-critical system software licensed under this
License.

"Life-Critical Function" means a function whose failure could directly
cause loss of life or permanent injury.

"Formal Verification" means mathematical proof of correctness for critical
properties.

"Fail-Operational" means the system continues to function safely after a
single component failure.

### 1. Permissions.

You may use, copy, modify, and distribute the Software for any lawful
purpose, subject to the life-critical conditions below.

### 2. Formal Verification.

Any Life-Critical Function must be Formally Verified for:
- **a)** Safety properties (nothing bad happens);
- **b)** Liveness properties (required behavior occurs);
- **c)** Real-time constraints (timing requirements met).

### 3. Redundancy.

Life-Critical Functions must be implemented with:
- **a)** At least triple redundancy for sensing and actuation;
- **b)** Diverse implementation to avoid common-mode failures;
- **c)** Fail-Operational capability after first failure.

### 4. Certification.

The Software must be certified by an accredited body for its intended
safety integrity level before deployment.

### 5. Disclosure.

You must document:
- All safety requirements and their verification;
- All known hazards and their mitigations;
- The certification standard and level achieved.

### 6. Termination.

Deployment of Life-Critical Functions without Formal Verification
terminates rights with no cure.

### 7. Disclaimer of Warranty.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF LIFE SAFETY.

### 8. Limitation of Liability.

IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR LOSS OF LIFE.

**END OF TERMS AND CONDITIONS**
