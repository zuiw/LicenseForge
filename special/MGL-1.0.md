# Multi-Generational License, Version 1.0 (MGL-1.0)

**Copyright (C) 2026 [Your Name or Organization]**

A license that requires long-term maintenance commitments, migration
guarantees, and support timelines across major versions.

## Preamble

The MGL addresses the problem of abandoned or breaking-upgrade software in
critical infrastructure.  It requires that maintainers commit to minimum
support timelines, provide migration paths between major versions, and
ensure that users are not stranded on unsupported versions without a
reasonable transition period.

## TERMS AND CONDITIONS

### 0. Definitions.

"This License" refers to version 1.0 of the Multi-Generational License
(MGL-1.0).

"The Software" means the project licensed under this License.

"Major Version" means a release that introduces breaking changes or removes
deprecated functionality.

"LTS Release" means a Long-Term Support version that receives security and
critical bug fixes for a defined period.

"Support Period" means the duration for which a version is guaranteed to
receive updates.

"Migration Path" means documented steps and tooling to transition from one
Major Version to the next.

### 1. Permissions.

You may use, copy, modify, and distribute the Software for any lawful
purpose, subject to the multi-generational conditions below.

### 2. LTS Commitment.

If you release Major Versions of the Software, you must designate each
Major Version as an LTS Release with a Support Period of at least:
- **a)** 3 years for the latest Major Version;
- **b)** 1 year for the previous Major Version after a new Major Version is
  released.

### 3. Migration Path.

When releasing a new Major Version, you must provide:
- **a)** A documented Migration Path from the previous version;
- **b)** Deprecation warnings at least one minor version before breaking
  changes;
- **c)** Backward-compatible APIs for at least one minor version cycle.

### 4. End-of-Life Notice.

You must provide at least 6 months notice before the end of the Support
Period for any LTS Release, including:
- Recommended upgrade target;
- Migration assistance or documentation;
- Security impact assessment.

### 5. Transparency.

You must maintain:
- A publicly accessible support schedule;
- A changelog with breaking changes clearly marked;
- A known issues list with planned resolutions.

### 6. Termination.

Failure to meet LTS commitments terminates rights.  A 120-day cure period
applies for maintainers to resume support.

### 7. Disclaimer of Warranty.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF FUTURE SUPPORT.

### 8. Limitation of Liability.

IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR MIGRATION-RELATED COSTS.

**END OF TERMS AND CONDITIONS**


## How to Apply These Terms

Include the following notice:

```
<Software name>
Copyright (C) <year> <author>
Licensed under the Multi-Generational License, version 1.0 (MGL-1.0).
LTS and migration path required for major versions.
Full terms: <URL>.
```
