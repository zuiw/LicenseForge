# Best Practice License, Version 1.0 (BPL-1.0)

**Copyright (C) 2026 [Your Name or Organization]**

A license that requires users to follow software engineering best practices:
automated testing, code review, CI/CD, and documentation.

## Preamble

The BPL ensures that software freedom is paired with software quality.
Anyone who modifies and distributes BPL-licensed software must follow basic
engineering best practices: automated tests for all changes, peer code
review, continuous integration, and up-to-date documentation.

## TERMS AND CONDITIONS

### 0. Definitions.

"This License" refers to version 1.0 of the Best Practice License (BPL-1.0).

"The Software" means the program licensed under this License.

"Best Practices" means the following engineering standards:
- **a)** All code changes must be reviewed by at least one person other than
  the author;
- **b)** All changes must include automated tests that exercise the change;
- **c)** A continuous integration system must verify all tests pass before
  distribution;
- **d)** Documentation must be updated to reflect changes;
- **e)** A changelog must be maintained;
- **f)** The software must use a version control system with a public
  history.

### 1. Permissions.

You may use, copy, and modify the Software for any lawful purpose.

### 2. Distribution Requirement.

If you distribute a modified version of the Software, you must:
- Follow Best Practices in the development of the modifications;
- Include documentation of any deviation from Best Practices and the
  rationale.

### 3. Minimum Test Coverage.

Modified versions distributed to others must maintain or exceed the test
coverage level of the original Software.  If the original Software's test
coverage is not documented, you must achieve at least 50% line coverage.

### 4. Code Review Record.

You must maintain a record of code reviews for all modifications, including
reviewer identity and approval date, and include this record in the
distribution.

### 5. Documentation.

You must update all documentation affected by your modifications, including
API documentation, README files, and deployment instructions.

### 6. Termination.

Failure to follow Best Practices for distributed modifications terminates
rights.  A 90-day cure period applies.

### 7. Disclaimer of Warranty.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF CODE QUALITY.

### 8. Limitation of Liability.

IN NO EVENT SHALL THE COPYRIGHT HOLDER BE LIABLE FOR ANY DAMAGES.

**END OF TERMS AND CONDITIONS**


## How to Apply These Terms

Include the following notice:

```
<Software name>
Copyright (C) <year> <author>
Licensed under the Best Practice License, version 1.0 (BPL-1.0).
Distributed modifications require code review, tests, and CI.
Full terms: <URL>.
```
