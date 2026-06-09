# Model License, Version 1.0 (MDL-1.0)

**Copyright (C) 2026 [Your Name or Organization]**

A license designed for AI/ML model weights, architectures, and associated
artifacts, addressing inference, distribution, fine-tuning, and commercial
deployment.

## Preamble

The MDL addresses the unique legal characteristics of AI models: the
distinction between architecture and weights, the difficulty of defining
"derived works" for fine-tuned models, and the obligations that arise when
a model is deployed as a service.  It provides a flexible framework for
model creators to control how their models are used, modified, and
distributed.

## TERMS AND CONDITIONS

### 0. Definitions.

"This License" refers to version 1.0 of the Model License (MDL-1.0).

"The Model" means the machine learning model, including architecture
definitions, trained parameters (weights), configuration files, and
associated documentation.

"Model Output" means any data, prediction, classification, generation, or
inference result produced by the Model.

"Derived Model" means:
- A model that is fine-tuned, adapted, or modified from the Model;
- A model that is trained on Model Output (distillation);
- A model that incorporates components of the Model's architecture;
- An ensemble that includes the Model.

"Inference Service" means any service that accepts input and returns Model
Output, whether via API, web interface, or batch processing.

### 1. Permissions.

Subject to the conditions below, you may:
- Use the Model for research, non-commercial, and commercial purposes;
- Modify the Model for internal use;
- Reproduce and distribute copies of the Model.

### 2. Derived Model Obligations.

If you create a Derived Model and distribute it or use it in an Inference
Service, you must:
- **a)** License the Derived Model under this License;
- **b)** Include attribution to the original Model;
- **c)** Document the nature and extent of the derivation;
- **d)** Provide the Derived Model weights and configuration.

### 3. Inference Service Disclosure.

If you operate an Inference Service using the Model (modified or
unmodified), you must:
- **a)** Clearly indicate to users that the service is powered by this
  Model;
- **b)** Provide a link to the Model source and license;
- **c)** Not misrepresent Model Output as human-generated.

### 4. Use Restrictions.

The copyright holder may designate specific prohibited use cases in the
License notice (e.g., surveillance, weapons, harmful content generation).

### 5. Termination.

Violation of Derived Model obligations or designated use restrictions
terminates all rights.  A 60-day cure period applies for non-restriction
violations.

### 6. Disclaimer of Warranty.

THE MODEL IS PROVIDED "AS IS", WITHOUT WARRANTY OF OUTPUT ACCURACY, SAFETY,
OR FITNESS FOR ANY PARTICULAR PURPOSE.

### 7. Limitation of Liability.

IN NO EVENT SHALL THE COPYRIGHT HOLDER BE LIABLE FOR ANY MODEL OUTPUT OR
DOWNSTREAM HARM.

**END OF TERMS AND CONDITIONS**


## How to Apply These Terms

Include the following notice in the model card or README:

```
<Model name> v<version>
Copyright (C) <year> <author>
Licensed under the Model License, version 1.0 (MDL-1.0).
Prohibited uses: [list or "none"].
Full terms: <URL>.
```
