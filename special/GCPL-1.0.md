# Governance Compliance License, Version 1.0 (GCPL-1.0)

**Copyright (C) 2026 [Your Name or Organization]**

A license for governance compliance tools requiring policy-as-code, automated enforcement, audit trails, and exception management.

## Preamble

The GCPL governs software that enforces organizational governance and compliance policies. It requires that policies be expressed as code (policy-as-code), enforced automatically, and fully auditable. It ensures that compliance is verifiable, consistent, and documented.

## TERMS AND CONDITIONS

### 0. Definitions.

"This License" refers to version 1.0 of the Governance Compliance License (GCPL-1.0).

"The Software" means the governance or compliance enforcement system licensed under this License.

"Policy" means a governance rule expressed as computable code.

"Compliance Check" means automated verification that a system meets defined Policies.

### 1. Permissions.

You may use, copy, modify, and distribute the Software, subject to the compliance conditions below.

### 2. Policy-as-Code.

Policies must be:
- **a)** Expressed as code in a version-controllable format;
- **b)** Human-readable alongside machine-executable;
- **c)** Testable against sample data;
- **d)** Documented with rationale.

### 3. Automated Enforcement.

The Software must:
- **a)** Run Compliance Checks on every change;
- **b)** Block changes that violate Policies;
- **c)** Support override with documented exception.

### 4. Audit Trail.

All Compliance Check results must be:
- **a)** Timestamped and cryptographically signed;
- **b)** Stored immutably for at least the retention period;
- **c)** Exportable for external audit.

### 5. Exception Management.

Policy exceptions must require documented justification, approval, and expiry date. Expired exceptions must be automatically re-challenged.

### 6. Termination.

Operating without audit trail or bypassing enforcement without documented exceptions terminates rights. A 90-day cure period applies.

### 7. Disclaimer of Warranty. Limitation of Liability.

THE SOFTWARE IS PROVIDED "AS IS". IN NO EVENT SHALL THE AUTHORS BE LIABLE.

**END OF TERMS AND CONDITIONS**
