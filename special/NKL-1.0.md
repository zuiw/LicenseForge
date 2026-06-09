# Network Kernel License, Version 1.0 (NKL-1.0)

**Copyright (C) 2026 [Your Name or Organization]**

A license for network protocols and infrastructure that mandates
interoperability and prohibits proprietary forks.

## Preamble

The NKL ensures that network protocols remain open and interoperable.  It
requires that any implementation of the protocol remain compatible with the
standard, that protocol extensions be published, and that fragmentation
through proprietary forks or vendor lock-in is prohibited.  It is designed
for network protocols, API specifications, and communication standards.

## TERMS AND CONDITIONS

### 0. Definitions.

"This License" refers to version 1.0 of the Network Kernel License
(NKL-1.0).

"The Protocol" means the network protocol, API specification, or
communication standard licensed under this License.

"Implementation" means any software that implements or uses the Protocol.

"Compatible Implementation" means an Implementation that correctly follows
the Protocol specification and can interoperate with other Implementations.

"Protocol Extension" means any addition or modification to the Protocol
beyond the base specification.

"Fork" means a divergent version of the Protocol that breaks
interoperability with the standard.

### 1. Permissions.

You may use, copy, modify, and distribute the Protocol for any lawful
purpose, subject to the interoperability conditions below.

### 2. Interoperability.

Any Implementation of the Protocol must be a Compatible Implementation.
You must not introduce changes that break interoperability with other
Implementations.

### 3. Extensions.

If you create a Protocol Extension, you must:
- **a)** Publish the extension specification publicly;
- **b)** License the extension under these same terms;
- **c)** Not use the extension to create vendor lock-in;
- **d)** Work toward standardization of the extension where appropriate.

### 4. Anti-Forking.

You may not create or distribute a Fork.  Modifications must remain
backward-compatible and interoperable with the standard Protocol.

### 5. Disclosure.

If you operate a service using the Protocol, you must:
- **a)** Disclose which version of the Protocol you implement;
- **b)** Publish any Protocol Extensions you use;
- **c)** Support interoperability testing upon request.

### 6. Termination.

Creating a non-interoperable Fork terminates all rights with no cure.

### 7. Disclaimer of Warranty.

THE PROTOCOL IS PROVIDED "AS IS", WITHOUT WARRANTY OF INTEROPERABILITY.

### 8. Limitation of Liability.

IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR INTEROPERABILITY FAILURES.

**END OF TERMS AND CONDITIONS**


## How to Apply These Terms

Include the following notice:

```
<Protocol name> v<version>
Copyright (C) <year> <author>
Licensed under the Network Kernel License, version 1.0 (NKL-1.0).
Interoperability required. Proprietary forks prohibited.
Full terms: <URL>.
```
