# Interoperability Standard License, Version 1.0 (ISL-1.0)

**Copyright (C) 2026 [Your Name or Organization]**

A license that requires users who modify the software to document any API
changes and maintain interoperability with the original version.

## Preamble

The ISL ensures that modified versions of the software remain interoperable
with the original and that APIs and data formats are fully documented.  It
prevents forking a project and changing its interfaces in undocumented ways
that fragment the user community.

## TERMS AND CONDITIONS

### 0. Definitions.

"This License" refers to version 1.0 of the Interoperability Standard
License (ISL-1.0).

"The Software" means the program licensed under this License.

"Public API" means any function, method, endpoint, interface, or protocol
exposed by the Software for use by other software.

"Data Format" means any file format, serialization scheme, or data structure
used by the Software for input, output, or storage.

"Documentation" means technical documentation sufficient for a third-party
developer to use the Public API or produce or consume the Data Format.

### 1. Permissions.

You may use, copy, modify, and distribute the Software for any purpose,
subject to the interoperability conditions below.

### 2. Interoperability Conditions.

**a) API Documentation.** If you add, modify, or remove any Public API,
you must document all changes in a publicly accessible location.

**b) Data Format Documentation.** If you modify any Data Format, you must
document the modified format.

**c) Backward Compatibility.** You may remove or change Public APIs or Data
Formats only if you provide a migration path, compatibility layer, or
conversion tool.

**d) No Lock-In.** You may not add a Public API or Data Format that is
covered by patents you hold without granting a royalty-free license to all
recipients.

### 3. Documentation Standards.

Documentation required by this section must be:
- Published in a publicly accessible repository;
- Written in clear, standard technical language;
- Updated within 30 days of the change.

### 4. Termination.

Failure to document API or Data Format changes after written notice
terminates rights under this License.  A 60-day cure period applies.

### 5. Disclaimer of Warranty.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF INTEROPERABILITY.

### 6. Limitation of Liability.

IN NO EVENT SHALL THE COPYRIGHT HOLDER BE LIABLE FOR ANY DAMAGES.

**END OF TERMS AND CONDITIONS**


## How to Apply These Terms

Include the following notice:

```
<Software name>
Copyright (C) <year> <author>
Licensed under the Interoperability Standard License, version 1.0 (ISL-1.0).
API changes must be documented.
Full terms: <URL>.
```
