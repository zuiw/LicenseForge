# Edge Computing License, Version 1.0 (ECL-1.0)

**Copyright (C) 2026 [Your Name or Organization]**

A license for edge computing software prioritizing offline-first operation,
local processing, and low-latency requirements.

## Preamble

The ECL addresses the unique constraints of edge computing environments.
Edge devices operate with limited connectivity, variable network quality,
and strict latency requirements.  This license requires that edge software
function offline, process data locally whenever feasible, and degrade
gracefully under network interruption.

## TERMS AND CONDITIONS

### 0. Definitions.

"This License" refers to version 1.0 of the Edge Computing License
(ECL-1.0).

"The Software" means the edge computing application, agent, or middleware
licensed under this License.

"Edge Device" means a computing device operating at the network edge,
typically with limited resources and intermittent connectivity.

"Offline Mode" means the ability to function without network connectivity.

"Cloud Dependency" means a feature that requires network connectivity to a
remote server for core functionality.

### 1. Permissions.

You may use, copy, modify, and distribute the Software for any lawful
purpose, subject to the edge computing conditions below.

### 2. Offline-First.

The Software must be designed to operate in Offline Mode.  Core
functionality must not depend on network connectivity.  If the Software has
Cloud Dependencies, you must:
- **a)** Clearly document which features require connectivity;
- **b)** Gracefully degrade when connectivity is lost;
- **c)** Cache and sync data when connectivity is restored.

### 3. Local Processing.

Data processing should occur on the Edge Device where feasible.  Data
should only be sent to the cloud when:
- Local processing is technically impractical;
- The user has explicitly consented;
- Aggregation is required for the application's primary function.

### 4. Resource Efficiency.

The Software must:
- **a)** Document minimum hardware requirements;
- **b)** Support configurable resource limits (CPU, memory, storage);
- **c)** Provide monitoring of resource consumption.

### 5. Connectivity Transparency.

The Software must:
- **a)** Indicate current connectivity status;
- **b)** Notify users before large data transfers;
- **c)** Support bandwidth-limiting configuration.

### 6. Termination.

Creating a Cloud Dependency that disables the Software's Offline Mode
terminates rights.  A 90-day cure period applies.

### 7. Disclaimer of Warranty.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF EDGE SUITABILITY.

### 8. Limitation of Liability.

IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR CONNECTIVITY-RELATED FAILURES.

**END OF TERMS AND CONDITIONS**


## How to Apply These Terms

Include the following notice:

```
<Edge Software name>
Copyright (C) <year> <author>
Licensed under the Edge Computing License, version 1.0 (ECL-1.0).
Offline-first and local data processing required.
Full terms: <URL>.
```
