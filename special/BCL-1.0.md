# Blockchain Contract License, Version 1.0 (BCL-1.0)

**Copyright (C) 2026 [Your Name or Organization]**

A license designed for smart contracts and blockchain applications, with
chain-specific disclosure and interaction provisions.

## Preamble

The BCL addresses the unique characteristics of blockchain software: code is
immutable once deployed, it interacts with financial assets, and it runs on
decentralized networks.  This license requires that smart contracts and
their source code be permanently verified on-chain, that modifications be
transparent, and that users be clearly informed of the contract's terms.

## TERMS AND CONDITIONS

### 0. Definitions.

"This License" refers to version 1.0 of the Blockchain Contract License
(BCL-1.0).

"The Contract" means any smart contract, decentralized application, or
blockchain-based software licensed under this License.

"Chain" means the blockchain network on which the Contract is deployed.

"Deployment" means the act of submitting the Contract to a Chain for
execution.

"On-Chain Verification" means that the source code or its verifiable hash
is published on the Chain itself or on a blockchain-based verification
service.

"User" means any person or contract that interacts with the Contract.

### 1. Source Code Verification.

**a) On-Chain Publication.** Before or simultaneously with Deployment, you
must publish the complete source code of the Contract in a publicly
accessible repository and register its cryptographic hash on the Chain
through a standard verification service (e.g., Etherscan verification or
equivalent).

**b) Build Verification.** You must provide reproducible build instructions
that allow any third party to verify that the deployed bytecode matches the
published source code.

**c) Dependency Disclosure.** All dependencies, libraries, and third-party
contracts used by the Contract must be listed with their exact versions and
license information.

### 2. Deployment and Modifications.

**a) Immutable Disclosure.** Once deployed, the source code must remain
publicly accessible for the lifetime of the Contract.

**b) Upgradable Contracts.** If the Contract uses a proxy or upgrade
pattern, the upgrade mechanism must be clearly documented in the source
code, and each upgrade must trigger fresh on-chain verification.

**c) Modification.** Modified versions of the Contract may be deployed
only if they are licensed under this License and their source is verified
on-chain.

### 3. User Notice.

Any interface, dApp, or application that interacts with the Contract must
display a clear notice:
- That the Contract is licensed under BCL-1.0;
- Where to find the verified source code;
- That the Contract is provided without warranty, including no guarantee
  of freedom from vulnerabilities.

### 4. Financial Risk Disclosure.

You must include a prominent notice in the source code and any user
interface that the Contract may hold or transfer financial assets, and that
users assume all risk of loss, including loss due to software defects.

### 5. Termination.

Violation of source verification obligations (sections 1 or 2) terminates
all rights under this License.  Given the immutable nature of blockchain
deployments, termination does not require removal of already-deployed
contracts, but further Deployment is prohibited.

### 6. Disclaimer of Warranty.

THE CONTRACT IS PROVIDED "AS IS", WITHOUT WARRANTY OF FREEDOM FROM
VULNERABILITIES, BUGS, OR FINANCIAL LOSS.

### 7. Limitation of Liability.

IN NO EVENT SHALL THE COPYRIGHT HOLDER BE LIABLE FOR ANY FINANCIAL LOSS,
UNAUTHORIZED TRANSACTIONS, OR OTHER DAMAGES ARISING FROM THE USE OF THE
CONTRACT.

**END OF TERMS AND CONDITIONS**


## How to Apply These Terms

Include the following notice in the contract source code and deployment
metadata:

```
// <Contract name> v<version>
// SPDX-License-Identifier: BCL-1.0
// Copyright (C) <year> <author>
// Licensed under the Blockchain Contract License, version 1.0 (BCL-1.0).
// Full terms: <URL>.
```
