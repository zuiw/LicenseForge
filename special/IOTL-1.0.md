# Internet of Things License, Version 1.0 (IOTL-1.0)

**Copyright (C) 2026 [Your Name or Organization]**

A license for IoT firmware and embedded software requiring firmware updateability, data transparency, and device security.

## Preamble

The IOTL addresses the unique challenges of Internet of Things software: devices must remain updateable after deployment, data collection must be transparent to users, and basic security practices must be followed. It prevents IoT devices from becoming abandonware or security hazards.

## TERMS AND CONDITIONS

### 0. Definitions.

"This License" refers to version 1.0 of the Internet of Things License (IOTL-1.0).

"The Software" means the firmware, embedded software, or IoT platform licensed under this License.

"IoT Device" means a physical device running the Software that connects to a network.

"Device Owner" means the person or entity that possesses the IoT Device.

"Collected Data" means any data generated or collected by the IoT Device.

### 1. Permissions.

You may use, copy, modify, and distribute the Software, subject to the IoT conditions below.

### 2. Firmware Updateability.

If you distribute the Software on an IoT Device, you must:
- **a)** Provide a mechanism for Device Owners to install firmware updates;
- **b)** Support updates for at least the device's stated support lifetime;
- **c)** Sign firmware updates cryptographically;
- **d)** Not prevent installation of alternative firmware unless required by law.

### 3. Data Transparency.

If the IoT Device collects or transmits data:
- **a)** Disclose exactly what data is Collected;
- **b)** Obtain informed consent from Device Owners;
- **c)** Allow Device Owners to access their Collected Data;
- **d)** Support local processing where feasible.

### 4. Security Requirements.

You must:
- **a)** Use secure boot and code signing;
- **b)** Provide security updates for critical vulnerabilities within 90 days;
- **c)** Publish a vulnerability disclosure policy;
- **d)** Remove hardcoded credentials and backdoors.

### 5. Minimum Functionality.

The Software must not cease essential functions solely due to cloud service termination. Critical local features must work offline.

### 6. Termination.

Distribution on IoT Devices that block firmware updates or conceal data collection terminates rights. A 90-day cure period applies.

### 7. Disclaimer of Warranty.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF FITNESS FOR ANY PARTICULAR IOT USE CASE.

### 8. Limitation of Liability.

IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR IoT-RELATED CLAIMS.

**END OF TERMS AND CONDITIONS**
