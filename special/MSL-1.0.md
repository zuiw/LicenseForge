# Microservice License, Version 1.0 (MSL-1.0)

**Copyright (C) 2026 [Your Name or Organization]**

A license designed for microservice architectures, requiring API contract
backward compatibility and service interface documentation.

## Preamble

The MSL addresses the special requirements of microservice ecosystems:
services communicate through APIs, and breaking changes can cascade across
distributed systems.  This license requires that API contracts remain
backward compatible, that interface changes be documented and versioned,
and that service dependencies be transparent.

## TERMS AND CONDITIONS

### 0. Definitions.

"This License" refers to version 1.0 of the Microservice License (MSL-1.0).

"The Software" means the microservice, API, or service component licensed
under this License.

"API Contract" means the defined interfaces, data schemas, and protocols
that the Software exposes for consumption by other services.

"Breaking Change" means any modification to the API Contract that would
cause existing consumers to fail or behave differently without modification.

"Consumer" means any service, application, or client that depends on the
Software's API Contract.

"Service Mesh" means the network of interdependent services that includes
the Software.

### 1. Permissions.

You may use, copy, modify, and distribute the Software for any lawful
purpose, subject to the microservice conditions below.

### 2. API Contract Backward Compatibility.

If you modify and distribute the Software, you must:
- **a)** Maintain backward compatibility with the previous API Contract;
- **b)** If a Breaking Change is necessary, provide a versioned API endpoint
  that continues to support the previous contract for at least 12 months;
- **c)** Document all API Contract changes in a changelog;
- **d)** Follow semantic versioning for the Software.

### 3. Interface Documentation.

The Software must include documentation covering:
- **a)** All API endpoints, methods, and schemas;
- **b)** Authentication and authorization requirements;
- **c)** Rate limits and throttling behavior;
- **d)** Error codes and error handling conventions.

### 4. Dependency Transparency.

You must document:
- All services the Software depends on;
- The version of each dependency;
- The nature of the dependency (required, optional, cached);
- Fallback behavior if dependencies are unavailable.

### 5. Health and Observability.

The Software must expose:
- A health check endpoint;
- Metrics in a standard format (e.g., Prometheus);
- Structured logging for debugging and monitoring.

### 6. Termination.

Breaking Changes without backward compatibility support terminate rights.
A 90-day cure period applies.

### 7. Disclaimer of Warranty.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF SERVICE AVAILABILITY.

### 8. Limitation of Liability.

IN NO EVENT SHALL THE COPYRIGHT HOLDER BE LIABLE FOR ANY SERVICE OUTAGES.

**END OF TERMS AND CONDITIONS**


## How to Apply These Terms

Include the following notice:

```
<Service name> v<version>
Copyright (C) <year> <author>
Licensed under the Microservice License, version 1.0 (MSL-1.0).
API backward compatibility required.
Full terms: <URL>.
```
