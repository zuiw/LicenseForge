# AI Safety License, Version 1.0 (AIL-1.0)

**Copyright (C) 2026 [Your Name or Organization]**

A license for AI/ML models and systems that requires safety testing,
alignment measures, and risk assessment before deployment.

## Preamble

The AIL addresses the growing risks of AI systems.  It permits research,
study, and non-commercial use freely, but requires that any deployment of
the AI system undergo safety testing, alignment evaluation, and risk
assessment.  High-risk deployments require independent audit.  The goal is
to foster open AI research while ensuring that deployed AI systems are
safe, aligned, and accountable.

## TERMS AND CONDITIONS

### 0. Definitions.

"This License" refers to version 1.0 of the AI Safety License (AIL-1.0).

"The Model" means the AI/ML model, weights, architecture, and associated
software licensed under this License.

"Deployment" means making the Model available to users or other systems,
whether through API, embedding, hosting, or distribution.

"Safety Evaluation" means systematic testing for:
- **a)** Capability to cause physical harm;
- **b)** Ability to produce misleading, deceptive, or harmful outputs;
- **c)** Robustness against adversarial inputs;
- **d)** Bias and fairness assessment;
- **e)** Alignment with intended use.

"Alignment Measure" means a technique to ensure the Model behaves in
accordance with human values and intended purposes, including RLHF,
constitutional AI, or equivalent.

"High-Risk Deployment" means any Deployment where:
- The Model could cause physical, financial, or psychological harm;
- The Model is used in safety-critical domains;
- The Model interacts with vulnerable populations;
- The Model makes or informs consequential decisions about individuals.

### 1. Permissions.

You may use, copy, modify, and study the Model for non-commercial research
and educational purposes.

### 2. Pre-Deployment Requirements.

Before any Deployment, you must:
- **a)** Conduct a Safety Evaluation;
- **b)** Implement Alignment Measures appropriate to the risk level;
- **c)** Document the Safety Evaluation results;
- **d)** Publish a model card or equivalent documentation.

### 3. High-Risk Deployment.

High-Risk Deployment additionally requires:
- **a)** Independent third-party audit of the Safety Evaluation;
- **b)** Ongoing monitoring and incident reporting;
- **c)** A publicly posted responsible AI policy;
- **d)** A mechanism for users to report harmful outputs.

### 4. Incident Reporting.

If a deployed Model causes harm, you must:
- Report the incident to the copyright holder within 72 hours;
- Publish a public incident report within 30 days.

### 5. Distribution.

If you distribute the Model, you must include a copy of this License and
document any safety measures implemented.

### 6. Termination.

Deployment without Safety Evaluation terminates all rights.  High-Risk
Deployment without audit terminates all rights.

### 7. Disclaimer of Warranty.

THE MODEL IS PROVIDED "AS IS", WITHOUT WARRANTY OF SAFETY OR ALIGNMENT.

### 8. Limitation of Liability.

IN NO EVENT SHALL THE COPYRIGHT HOLDER BE LIABLE FOR ANY HARM CAUSED BY
DEPLOYED AI SYSTEMS.

**END OF TERMS AND CONDITIONS**


## How to Apply These Terms

Include the following notice in the model card or README:

```
<Model name> v<version>
Copyright (C) <year> <author>
Licensed under the AI Safety License, version 1.0 (AIL-1.0).
Safety evaluation required before deployment.
Full terms: <URL>.
```
