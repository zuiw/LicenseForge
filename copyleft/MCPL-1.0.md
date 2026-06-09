# Medical Copyleft License, Version 1.0 (MCPL-1.0)

**Copyright (C) 2026 [Your Name or Organization]**

This license is designed for medical software and health technology, combining
strong copyleft protection with mandatory patient safety, clinical validation,
and audit transparency provisions.

## Preamble

Medical software can directly affect patient health and safety.  The MCPL
ensures that modifications to medical software are disclosed, validated, and
traceable.  It requires clinical validation of modifications, mandates audit
logging, and prohibits use in unauthorized clinical contexts.  Its goal is
to foster open-source medical technology without compromising patient safety.

## TERMS AND CONDITIONS

### 0. Definitions.

"This License" refers to version 1.0 of the Medical Copyleft License (MCPL-1.0).

"The Software" means any software, algorithm, or digital health technology
licensed under this License that is intended for clinical, diagnostic,
therapeutic, or health-management purposes.

"Clinical Validation" means documented testing demonstrating that the Software
performs its intended clinical function within defined performance bounds.

"Adverse Event" means any undesirable clinical outcome associated with the
use of the Software.

"Modification" includes changes to clinical algorithms, decision thresholds,
user interfaces affecting clinical interpretation, data processing pipelines,
and any other change that could affect clinical performance.

### 1. Basic Permissions.

You may use, study, and modify the Software for any lawful purpose, subject
to the conditions of this License.

### 2. Source Code and Clinical Transparency.

The Corresponding Source includes all source code, training data, validation
datasets, clinical performance metrics, and all documentation required for
clinical validation.

### 3. Clinical Validation Requirement.

If you distribute a modified version of the Software or use a modified version
in a clinical setting, you must:

- **a)** Perform Clinical Validation of the modified version;
- **b)** Document all changes and their clinical rationale;
- **c)** Publish the Clinical Validation results alongside the Corresponding
  Source;
- **d)** Maintain a publicly accessible changelog that includes clinical
  impact assessments.

### 4. Adverse Event Reporting.

If you become aware of an Adverse Event associated with the Software (modified
or unmodified), you must:

- **a)** Report the event to the original copyright holder within 72 hours;
- **b)** Document the event in the public changelog;
- **c)** If the event is attributable to a modification, immediately revert
  or fix the modification.

### 5. Conveying Modified Versions.

Modified versions must be licensed under this License.  In addition to the
source disclosure requirements of standard copyleft licenses, you must include
the Clinical Validation report and adverse event history with each
distribution.

### 6. Prohibited Uses.

You may not use the Software:
- **a)** In any clinical context not explicitly validated;
- **b)** In a manner that disables or circumvents safety features;
- **c)** Without maintaining the audit trail required by applicable medical
  device regulations.

### 7. Regulatory Compliance.

The Software is provided without regulatory clearance.  You are responsible
for obtaining any required regulatory approvals (FDA, CE, etc.) before using
the Software in a clinical context.  The copyright holder makes no
representation regarding regulatory compliance.

### 8. Termination.

Violation of patient safety provisions (sections 3, 4, or 6) results in
immediate and permanent termination.  Other violations have a 30-day cure
period for a first offense.

### 9. Audit Rights.

The copyright holder or an independent auditor may inspect your use of the
Software for compliance with this License, upon reasonable notice and no
more than once per calendar year.

### 10. Disclaimer of Warranty.

THE SOFTWARE IS NOT APPROVED FOR ANY SPECIFIC CLINICAL USE WITHOUT
INDEPENDENT VALIDATION.  THERE IS NO WARRANTY, EXPRESS OR IMPLIED.

### 11. Limitation of Liability.

IN NO EVENT SHALL THE COPYRIGHT HOLDER BE LIABLE FOR ANY CLINICAL OUTCOMES,
PATIENT HARM, OR OTHER DAMAGES ARISING FROM THE USE OF THE SOFTWARE.

**END OF TERMS AND CONDITIONS**


## How to Apply These Terms

Include the following notice in every source file, and include the full
license text as `LICENSE`:

```
<Software name> — Medical Software
Copyright (C) <year> <author>

This software is licensed under the Medical Copyleft License, version 1.0
(MCPL-1.0).  It is not FDA/CE cleared.  Clinical validation is required
before clinical use.  Full terms: <URL to license text>.
```
