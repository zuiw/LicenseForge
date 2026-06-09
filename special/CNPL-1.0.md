# Cloud Native Platform License, Version 1.0 (CNPL-1.0)

**Copyright (C) 2026 [Your Name or Organization]**

A license for cloud-native platforms and container orchestration tools requiring horizontal scalability, observability, and declarative configuration.

## Preamble

The CNPL governs cloud-native infrastructure platforms. It requires horizontal scalability, built-in observability (metrics, logs, traces), and declarative configuration management. It ensures that cloud-native tools follow established operational patterns and integrate with standard ecosystems.

## TERMS AND CONDITIONS

### 0. Definitions.

"This License" refers to version 1.0 of the Cloud Native Platform License (CNPL-1.0).

"The Software" means the cloud-native platform or orchestration tool licensed under this License.

"Horizontal Scalability" means the ability to add more instances to handle increased load.

"Declarative Configuration" means desired-state configuration managed by the platform.

### 1. Permissions.

You may use, copy, modify, and distribute the Software, subject to the cloud-native conditions below.

### 2. Horizontal Scalability.

The Software must support Horizontal Scalability without requiring downtime or manual reconfiguration, and must document scaling limits and performance characteristics.

### 3. Observability.

The Software must expose:
- **a)** Health and readiness endpoints;
- **b)** Metrics in a standard format (e.g., OpenMetrics);
- **c)** Structured logs;
- **d)** Distributed tracing context propagation.

### 4. Declarative Configuration.

All configuration must be Declarative, version-controllable, and support dry-run validation before application.

### 5. API Stability.

The Software's API must follow semantic versioning, with breaking changes reserved for major version bumps and deprecation warnings provided for at least one minor version cycle.

### 6. Termination.

Distributing without Horizontal Scalability or Declarative Configuration support terminates rights. A 90-day cure period applies.

### 7. Disclaimer of Warranty. Limitation of Liability.

THE SOFTWARE IS PROVIDED "AS IS". IN NO EVENT SHALL THE AUTHORS BE LIABLE.

**END OF TERMS AND CONDITIONS**
