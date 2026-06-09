# Real-Time Operating System License, Version 1.0 (RTOSL-1.0)

**Copyright (C) 2026 [Your Name or Organization]**

A license for real-time operating systems and embedded kernels requiring deterministic behavior, priority scheduling guarantees, and interrupt latency disclosure.

## Preamble

The RTOSL governs RTOS kernels and embedded software where timing guarantees are critical. It requires documentation of scheduling behavior, interrupt latency, and worst-case execution times, so that integrators can make informed decisions about safety-critical deployments.

## TERMS AND CONDITIONS

### 0. Definitions.

"This License" refers to version 1.0 of the Real-Time Operating System License (RTOSL-1.0).

"The Software" means the RTOS kernel or real-time framework licensed under this License.

"Deterministic Behavior" means that task execution times have bounded, predictable variance.

"Worst-Case Execution Time" means the maximum time a task can take to complete under defined conditions.

### 1. Permissions.

You may use, copy, modify, and distribute the Software, subject to the RTOS conditions below.

### 2. Determinism Documentation.

You must document:
- **a)** Scheduling policy and guarantees;
- **b)** Interrupt latency and jitter;
- **c)** Worst-Case Execution Time for all system calls;
- **d)** Priority inversion prevention mechanisms.

### 3. Priority Scheduling.

The Software must support:
- **a)** Preemptive priority-based scheduling;
- **b)** Configurable task priorities;
- **c)** Priority inheritance or ceiling protocol.

### 4. Interrupt Handling.

Interrupt service routines must have bounded execution time, and the Software must document maximum interrupt latency under load.

### 5. Termination.

Distributing without determinism documentation terminates rights. A 90-day cure period applies.

### 6. Disclaimer of Warranty. Limitation of Liability.

THE SOFTWARE IS PROVIDED "AS IS". IN NO EVENT SHALL THE AUTHORS BE LIABLE.

**END OF TERMS AND CONDITIONS**
