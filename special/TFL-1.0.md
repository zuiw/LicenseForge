# Trusted Firmware License, Version 1.0 (TFL-1.0)

**Copyright (C) 2026 [Your Name or Organization]**

A license for firmware that requires secure boot, cryptographic signing, and
verified execution.

## Preamble

The TFL addresses the security requirements of firmware in embedded devices,
IoT systems, and critical infrastructure.  It requires that firmware be
cryptographically signed, that updates be verified, that secure boot be
implemented, and that users can verify the authenticity and integrity of the
firmware running on their devices.

## TERMS AND CONDITIONS

### 0. Definitions.

"This License" refers to version 1.0 of the Trusted Firmware License
(TFL-1.0).

"The Firmware" means the firmware image, bootloader, or embedded software
licensed under this License.

"Secure Boot" means a process that verifies the cryptographic signature of
the Firmware before execution.

"Code Signing" means the practice of digitally signing the Firmware to
verify its authenticity and integrity.

"Update Mechanism" means the process by which the Firmware can be updated
or patched after initial deployment.

### 1. Permissions.

You may use, copy, modify, and distribute the Firmware for any lawful
purpose, subject to the trusted firmware conditions below.

### 2. Secure Boot.

If you distribute the Firmware for use on physical hardware, you must
implement Secure Boot that:
- **a)** Verifies the Firmware signature before execution;
- **b)** Refuses to run unsigned or untrusted Firmware;
- **c)** Provides a secure recovery mechanism.

### 3. Code Signing.

The Firmware must be Code Signed using:
- A key management system with access controls;
- A certificate chain rooted in a trusted authority or hardware root of
  trust;
- Signatures that cover the entire Firmware image.

### 4. Secure Updates.

The Update Mechanism must:
- **a)** Verify signatures before applying updates;
- **b)** Support rollback to a known-good version;
- **c)** Prevent downgrade attacks;
- **d)** Sign and encrypt update packages.

### 5. Transparency.

You must document:
- The Secure Boot implementation details;
- The Code Signing key management process;
- The Update Mechanism architecture;
- Known security limitations.

### 6. Termination.

Distribution without Secure Boot terminates rights.  A 90-day cure period
applies.

### 7. Disclaimer of Warranty.

THE FIRMWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF SECURITY.

### 8. Limitation of Liability.

IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR FIRMWARE SECURITY FAILURES.

**END OF TERMS AND CONDITIONS**


## How to Apply These Terms

Include the following notice:

```
<Firmware name> v<version>
Copyright (C) <year> <author>
Licensed under the Trusted Firmware License, version 1.0 (TFL-1.0).
Secure boot and code signing required.
Full terms: <URL>.
```
