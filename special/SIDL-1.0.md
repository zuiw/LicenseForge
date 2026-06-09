# Service Mesh Sidecar License, Version 1.0 (SIDL-1.0)

**Copyright (C) 2026 [Your Name or Organization]**

A license for service mesh and sidecar proxy software requiring transparent traffic management, observability, and security policy enforcement.

## Preamble

The SIDL governs service mesh sidecar proxies and traffic management software. It requires transparent traffic routing (no hidden modifications), comprehensive observability (traffic metrics, tracing, access logs), and enforceable security policies (mTLS, authorization, rate limiting). It ensures that service mesh software is trustworthy and auditable.

## TERMS AND CONDITIONS

### 0. Definitions.

"This License" refers to version 1.0 of the Service Mesh Sidecar License (SIDL-1.0).

"The Software" means the service mesh sidecar or traffic proxy licensed under this License.

"Sidecar" means a proxy that intercepts network traffic for a service.

"Traffic Policy" means rules governing routing, load balancing, and fault handling.

### 1. Permissions.

You may use, copy, modify, and distribute the Software, subject to the service mesh conditions below.

### 2. Traffic Transparency.

The Sidecar must:
- **a)** Log all intercepted traffic metadata;
- **b)** Disclose any traffic modification (headers, redirects, retries);
- **c)** Support passive mode for monitoring without modification.

### 3. Observability.

The Software must expose:
- **a)** Request-level metrics (latency, error rate, throughput);
- **b)** Distributed tracing context propagation;
- **c)** Access logs with source, destination, and decision;
- **d)** Control plane metrics for policy changes.

### 4. Security Policies.

The Software must support:
- **a)** mTLS between Sidecars;
- **b)** Service-level authorization (RBAC/ABAC);
- **c)** Rate limiting per service or route;
- **d)** Circuit breaking for fault isolation.

### 5. Termination.

Operating without traffic transparency or with hidden traffic modification terminates rights. A 60-day cure period applies.

### 6. Disclaimer of Warranty. Limitation of Liability.

THE SOFTWARE IS PROVIDED "AS IS". IN NO EVENT SHALL THE AUTHORS BE LIABLE.

**END OF TERMS AND CONDITIONS**
