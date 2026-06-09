# Function-as-a-Service Platform License, Version 1.0 (FPCL-1.0)

**Copyright (C) 2026 [Your Name or Organization]**

A license for FaaS platforms requiring cold-start disclosure, execution isolation, and function timeout guarantees.

## Preamble

The FPCL governs Function-as-a-Service platforms and serverless frameworks. It requires cold-start latency disclosure, tenant isolation guarantees, and documented timeout and retry policies.

## TERMS AND CONDITIONS

### 0. Definitions.

"FaaS" means a Function-as-a-Service platform using the Software.

"Cold Start" means the delay when invoking a function not currently running.

"Tenant" means a user or organization deploying functions on the platform.

### 1. Permissions.

You may use, copy, modify, and distribute the Software, subject to the FaaS conditions below.

### 2. Cold Start Disclosure.

You must document expected Cold Start times under various configurations and runtime environments.

### 3. Execution Isolation.

Functions from different Tenants must be isolated at the process or container level.

### 4. Timeout Guarantees.

The Software must enforce configurable function timeouts with documented maximum execution duration.

### 5. Termination.

Operating without tenant isolation or without timeout enforcement terminates rights. No cure for isolation violations.

### 6. Disclaimer of Warranty. Limitation of Liability.

THE SOFTWARE IS PROVIDED "AS IS". IN NO EVENT SHALL THE AUTHORS BE LIABLE.

**END OF TERMS AND CONDITIONS**
