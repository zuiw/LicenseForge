# Blockchain Oracle License, Version 1.0 (CHNL-1.0)

**Copyright (C) 2026 [Your Name or Organization]**

A license for blockchain oracle software requiring data source transparency, redundancy, fraud detection, and timely price updates.

## Preamble

The CHNL governs oracle systems that bridge blockchain smart contracts with external data. It requires disclosure of all data sources, redundancy across multiple independent sources, fraud detection mechanisms, and guaranteed update frequencies. It ensures that oracle-dependent protocols can trust the data they receive.

## TERMS AND CONDITIONS

### 0. Definitions.

"This License" refers to version 1.0 of the Blockchain Oracle License (CHNL-1.0).

"The Software" means the oracle system, data feed, or price oracle licensed under this License.

"Data Source" means the origin of data reported by the Oracle.

"Staked Asset" means cryptocurrency deposited as collateral for honest oracle reporting.

### 1. Permissions.

You may use, copy, modify, and distribute the Software, subject to the oracle conditions below.

### 2. Source Transparency.

The Software must document:
- **a)** All Data Sources for each feed;
- **b)** Data aggregation methodology (median, TWAP, etc.);
- **c)** Update frequency and triggers;
- **d)** Deviation thresholds for updates.

### 3. Redundancy.

Each data feed must aggregate from at least three independent Data Sources. If a source fails, the remaining sources must still produce reliable output.

### 4. Fraud Detection.

If Staked Assets are used, the Software must implement:
- **a)** Dispute windows for challenged data;
- **b)** Slashing conditions for fraudulent reporting;
- **c)** Economic penalties proportional to stake.

### 5. Timeliness.

The Software must guarantee maximum staleness for each data feed and provide alerts when feeds become stale.

### 6. Termination.

Operating with a single Data Source or without fraud detection terminates rights. A 30-day cure period applies.

### 7. Disclaimer of Warranty. Limitation of Liability.

THE SOFTWARE IS PROVIDED "AS IS". IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR ORACLE-RELATED LOSSES.

**END OF TERMS AND CONDITIONS**
