# Model Context Protocol License, Version 1.0 (MCPL-1.0)

**Copyright (C) 2026 [Your Name or Organization]**

A license designed for Model Context Protocol (MCP) servers, tools,
resources, and transport layers that enable AI models to interact with
external systems.

## Preamble

The MCPL is designed for the Model Context Protocol ecosystem: servers that
expose tools and resources to AI models, clients that connect to these
servers, and the transport layers that enable communication.  It ensures
that MCP components remain interoperable, that tool capabilities are
transparently documented, and that user data flowing through MCP is
protected.

## TERMS AND CONDITIONS

### 0. Definitions.

"This License" refers to version 1.0 of the Model Context Protocol License
(MCPL-1.0).

"The Component" means the MCP server, client, tool, resource, or transport
implementation licensed under this License.

"MCP" means the Model Context Protocol as defined by the relevant protocol
specification.

"Tool" means an MCP endpoint that performs an action on behalf of an AI
model, including reading, writing, transforming, or querying external
systems.

"Resource" means an MCP endpoint that provides data or content to an AI
model.

"Transport" means the communication layer (stdio, SSE, WebSocket, HTTP, or
equivalent) that connects MCP clients and servers.

"User Context" means any data, prompts, or user information transmitted
through the Component.

### 1. Permissions.

You may use, copy, modify, and distribute the Component for any lawful
purpose, subject to the conditions below.

### 2. Protocol Compliance.

The Component must implement the MCP specification as published.  Modified
versions must:
- **a)** Clearly document any protocol extensions or deviations;
- **b)** Remain interoperable with unmodified MCP clients/servers;
- **c)** Maintain backward compatibility where feasible.

### 3. Tool Documentation.

If the Component provides Tools, you must document for each Tool:
- Its name, description, and input schema;
- What side effects the Tool may have on external systems;
- Any authentication or authorization requirements;
- Rate limits or usage constraints.

### 4. User Data Transparency.

If the Component transmits or stores User Context, you must:
- Document what data is transmitted and to which services;
- Not transmit User Context to third parties without disclosure;
- Provide users with control over what context is shared;
- Implement encryption for sensitive data in transit.

### 5. Security Best Practices.

The Component must:
- Validate all inputs from AI models before acting on them;
- Implement appropriate authorization checks for destructive operations;
- Log actions taken on behalf of AI models;
- Provide mechanisms for rate limiting and abuse prevention.

### 6. Termination.

Introduction of protocol incompatibility or undisclosed data transmission
terminates all rights.  A 60-day cure period for other violations.

### 7. Disclaimer of Warranty.

THE COMPONENT IS PROVIDED "AS IS", WITHOUT WARRANTY OF MCP COMPATIBILITY.

### 8. Limitation of Liability.

IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY ACTIONS PERFORMED BY TOOLS.

**END OF TERMS AND CONDITIONS**


## How to Apply These Terms

Include the following notice:

```
<MCP Component name> v<version>
Copyright (C) <year> <author>
Licensed under the Model Context Protocol License, version 1.0 (MCPL-1.0).
Full terms: <URL>.
```
