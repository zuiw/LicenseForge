# Robotics License, Version 1.0 (RBL-1.0)

**Copyright (C) 2026 [Your Name or Organization]**

A license for robotics software requiring physical safety, emergency stops,
and human-robot interaction safeguards.

## Preamble

The RBL addresses the unique safety requirements of robotics.  Unlike pure
software, robots operate in the physical world and can cause bodily harm or
property damage.  This license requires that robotics software implement
physical safety mechanisms, emergency stop functionality, collision
avoidance, and human-robot interaction safeguards.

## TERMS AND CONDITIONS

### 0. Definitions.

"This License" refers to version 1.0 of the Robotics License (RBL-1.0).

"The Software" means the robotics software, control system, or middleware
licensed under this License.

"Robot" means any physical machine controlled by the Software that can
move or apply force in the physical world.

"Emergency Stop" means a safety mechanism that immediately halts all
dangerous motion and renders the Robot safe.

"Safety Zone" means a designated area where human presence is detected and
the Robot adjusts its behavior accordingly.

### 1. Permissions.

You may use, copy, modify, and distribute the Software for any lawful
purpose, subject to the robotics safety conditions below.

### 2. Physical Safety.

If you deploy the Software on a Robot, you must implement:
- **a)** Emergency Stop functionality that is easily accessible and clearly
  marked;
- **b)** Collision detection and automatic halt;
- **c)** Speed and force limiting based on Safety Zone configuration;
- **d)** Fail-safe behavior on power loss or communication failure.

### 3. Human-Robot Interaction.

The Robot must:
- **a)** Clearly indicate when it is operating autonomously;
- **b)** Provide visual or audible warnings when humans enter the Safety
  Zone;
- **c)** Yield to human operators in shared spaces;
- **d)** Cease operation if safety sensors are compromised.

### 4. Safety Documentation.

You must document:
- **a)** All safety features and their specifications;
- **b)** Known failure modes and their probabilities;
- **c)** Safe operating conditions and environments;
- **d)** Required maintenance intervals for safety systems.

### 5. Software Integrity.

Safety-critical components must be:
- Verified through code review or formal methods;
- Tested under simulated fault conditions;
- Versioned and changelogged with safety implications noted.

### 6. Termination.

Distribution without Emergency Stop functionality terminates rights.
No cure period applies for safety-critical violations.

### 7. Disclaimer of Warranty.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF SAFE OPERATION.

### 8. Limitation of Liability.

IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR ROBOT-RELATED INJURIES.

**END OF TERMS AND CONDITIONS**


## How to Apply These Terms

Include the following notice:

```
<Robot Software name>
Copyright (C) <year> <author>
Licensed under the Robotics License, version 1.0 (RBL-1.0).
Physical safety and emergency stop required.
Full terms: <URL>.
```
