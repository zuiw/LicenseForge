# Smart Contract Security License, Version 2.0 (SCL-2.0)

**Copyright (C) 2026 [Your Name or Organization]**

A license for smart contracts requiring mandatory security audits,
vulnerability disclosure, and user protection mechanisms.

## Preamble

The SCL-2.0 builds on the principles of SCL-1.0 (Security Compliance) with
specific requirements for smart contracts and decentralized applications.
Smart contracts manage financial assets and cannot be patched after
deployment.  This license requires mandatory security audits, formal
verification where feasible, bug bounties, timelocks for upgrades, and
insurance or compensation mechanisms for user losses.

## TERMS AND CONDITIONS

### 0. Definitions.

"This License" refers to version 2.0 of the Smart Contract Security License
(SCL-2.0).

"The Contract" means the smart contract, decentralized application, or
blockchain-based software licensed under this License.

"Security Audit" means a professional review of the Contract's source code
by an independent third-party security firm.

"Formal Verification" means mathematical proof that the Contract's code
behaves according to its specification.

"Timelock" means a mechanism that delays execution of sensitive operations
for a pre-configured period.

"User Loss" means financial loss suffered by a user due to a bug or
vulnerability in the Contract.

### 1. Permissions.

You may use, copy, modify, and distribute the Contract for any lawful
purpose, subject to the smart contract security conditions below.

### 2. Mandatory Audit.

Before deploying the Contract to a production network, you must:
- **a)** Obtain a Security Audit from a reputable firm;
- **b)** Disclose the audit report publicly;
- **c)** Fix or document all findings before deployment.

### 3. Formal Verification.

If the Contract manages assets exceeding $1,000,000 in total value locked,
you must conduct Formal Verification of the Contract's critical functions.

### 4. Bug Bounty.

You must maintain a public bug bounty program that:
- **a)** Covers all deployed Contract versions;
- **b)** Offers rewards commensurate with risk severity;
- **c)** Has a clear disclosure and resolution process.

### 5. Timelock.

All upgradeable contracts must implement a Timelock of at least 48 hours
for administrative operations.

### 6. User Protection.

If User Loss occurs due to a Contract vulnerability, you must:
- **a)** Disclose the incident within 24 hours;
- **b)** Freeze affected functionality where possible;
- **c)** Implement a compensation process for affected users.

### 7. Termination.

Deployment without Security Audit terminates rights with no cure.

### 8. Disclaimer of Warranty.

THE CONTRACT IS PROVIDED "AS IS", WITHOUT WARRANTY OF SECURITY.

### 9. Limitation of Liability.

IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR USER FINANCIAL LOSSES.

**END OF TERMS AND CONDITIONS**


## How to Apply These Terms

Include the following notice:

```
<Contract name>
Copyright (C) <year> <author>
Licensed under the Smart Contract Security License, version 2.0 (SCL-2.0).
Mandatory audit, bug bounty, and timelock required.
Full terms: <URL>.
```
