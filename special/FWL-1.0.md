# Firmware License, Version 1.0 (FWL-1.0)

**Copyright (C) 2026 [Your Name or Organization]**

A license designed for firmware, bootloaders, drivers, and embedded
software, with requirements for device access and replaceability.

## Preamble

The FWL is designed for the unique constraints of embedded and firmware
software.  It requires that devices running the firmware allow users to
replace the firmware with modified versions, that debugging interfaces are
not locked, and that the complete firmware build environment is published.
It is inspired by the "right to repair" and "firmware freedom" movements.

## TERMS AND CONDITIONS

### 0. Definitions.

"This License" refers to version 1.0 of the Firmware License (FWL-1.0).

"The Firmware" means the firmware, bootloader, driver, or embedded software
licensed under this License.

"The Device" means the hardware device on which the Firmware is intended
to run.

"Installation Information" means all methods, procedures, authorization
keys, and credentials required to install, modify, or replace the Firmware
on the Device.

"Debug Interface" means any hardware or software interface that allows
development, debugging, or low-level access to the Device.

### 1. Permissions.

You may use, copy, modify, and distribute the Firmware, subject to the
hardware freedom conditions below.

### 2. Firmware Replaceability.

If you distribute the Firmware pre-installed on a Device, you must:
- **a)** Provide Installation Information that enables the Device owner to
  replace the Firmware with a modified version;
- **b)** Not implement any technical measure that prevents the Device owner
  from installing modified firmware;
- **c)** Publish the Installation Information in a publicly accessible
  location.

### 3. Debug Interface.

You must document and disclose any Debug Interface present on the Device.
You may not disable or lock Debug Interfaces after the warranty period.

### 4. Build Environment.

You must publish the complete build environment toolchain, including
compiler versions, linker scripts, and configuration files required to
reproduce the exact firmware binary.

### 5. Combined Devices.

If the Device contains additional software (application layer, user
interface), the firmware obligations of this License apply only to the
Firmware layer.

### 6. Termination.

Failure to provide Installation Information or locking a Device against
firmware replacement terminates all rights.  A 90-day cure period applies.

### 7. Disclaimer of Warranty.

THE FIRMWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF DEVICE COMPATIBILITY.

### 8. Limitation of Liability.

IN NO EVENT SHALL THE COPYRIGHT HOLDER BE LIABLE FOR ANY DAMAGES.

**END OF TERMS AND CONDITIONS**


## How to Apply These Terms

Include the following notice:

```
<Firmware name> v<version>
Copyright (C) <year> <author>
Licensed under the Firmware License, version 1.0 (FWL-1.0).
Devices must allow firmware replacement.
Full terms: <URL>.
```
