# Infrastructure as Code License, Version 1.0 (IACL-1.0)

**Copyright (C) 2026 [Your Name or Organization]**

A license for Infrastructure as Code tools requiring idempotency, state management, drift detection, and dry-run support.

## Preamble

The IACL governs Infrastructure as Code (IaC) software. It requires idempotent operations (applying the same configuration multiple times produces the same result), state management for tracking infrastructure, drift detection to identify manual changes, and dry-run support for safe previews. It ensures infrastructure management is reliable and auditable.

## TERMS AND CONDITIONS

### 0. Definitions.

"This License" refers to version 1.0 of the Infrastructure as Code License (IACL-1.0).

"The Software" means the IaC tool or provisioning system licensed under this License.

"Idempotency" means applying the same configuration repeatedly produces the same infrastructure state.

"Drift" means the difference between the declared configuration and actual infrastructure.

### 1. Permissions.

You may use, copy, modify, and distribute the Software, subject to the IaC conditions below.

### 2. Idempotency.

The Software must guarantee Idempotency: applying the same configuration multiple times must not create duplicate resources or cause errors. Any operations that cannot be idempotent must be clearly documented.

### 3. State Management.

The Software must:
- **a)** Maintain an accurate state representation;
- **b)** Support state locking for concurrent operations;
- **c)** Provide state backup and recovery mechanisms;
- **d)** Encrypt sensitive data in state.

### 4. Drift Detection.

The Software must support detecting Drift between declared and actual infrastructure and provide remediation options.

### 5. Dry-Run Support.

The Software must provide a dry-run or preview mode showing what changes would be made without applying them.

### 6. Termination.

Distributing without Idempotency guarantees or state management terminates rights. A 90-day cure period applies.

### 7. Disclaimer of Warranty. Limitation of Liability.

THE SOFTWARE IS PROVIDED "AS IS". IN NO EVENT SHALL THE AUTHORS BE LIABLE.

**END OF TERMS AND CONDITIONS**
