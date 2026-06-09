# Strong Affero General Public License for Data, Version 1.0 (SAGPL-Data)

**Copyright (C) 2026 [Your Name or Organization]**

This license is a variant of the Strong Affero General Public License, version
1.0, adapted for datasets, machine learning models, training data, and
AI/ML systems.  It extends the copyleft concept to training data, model
weights, preprocessing pipelines, and inference outputs.

## Preamble

The Strong Affero General Public License for Data, version 1.0, extends the
principles of copyleft to the data and machine learning domain.  In an era
where data and models are as valuable as code, this license ensures that all
components of an AI/ML system—training data, preprocessing scripts, model
architectures, trained weights, and inference pipelines—remain freely available
for the community to inspect, modify, and improve.  Any use of a model or
dataset triggers full disclosure of all components required to reproduce and
modify it.

## TERMS AND CONDITIONS

### 0. Definitions.

"This License" refers to version 1.0 of the Strong Affero General Public
License for Data (SAGPL-Data).

"The Work" means any copyrightable work licensed under this License, which may
include datasets, model weights, training code, preprocessing scripts,
inference pipelines, or any combination thereof.  Each licensee is addressed as
"you".

"Dataset" means any collection of data, whether structured or unstructured,
that is used or was used in the creation, training, validation, or testing of
the Work.  This includes raw data, annotated data, synthetic data,
augmentations, splits, and metadata.

"Model" means any machine learning model, neural network, statistical model,
or other learned representation, including all trained parameters, weights,
biases, architecture definitions, and hyperparameter configurations.

"Derived Model" means any model that is:
- a) Fine-tuned, adapted, or otherwise modified from the Work;
- b) Trained using Output from the Work (including knowledge distillation);
- c) A ensemble or combination that includes the Work;
- d) Trained on a Dataset that is itself a covered work.

"Output" means any data, prediction, classification, generation, embedding, or
other result produced by running a Model licensed under this License.

"Inference Service" means any service that accepts input and returns Output
from a Model, whether accessed via API, web interface, batch processing, or
any other mechanism.

"Training Pipeline" means all scripts, configurations, and procedures used to
train, validate, and test a Model, including data preprocessing, augmentation,
training loops, evaluation metrics, and environment specifications.

"Corresponding Materials" means all components required to fully reproduce,
understand, and modify the Work, including:
- The complete source code of the Training Pipeline;
- The complete Dataset (including all splits);
- Model architecture definitions;
- Complete trained Model weights and parameters;
- All preprocessing and postprocessing scripts;
- All evaluation and benchmarking scripts;
- Complete environment specification (hardware, software, dependencies);
- All experimental logs and configuration files;
- A reproducible build/training environment.

### 1. Scope and Coverage.

**1.1 Components.** Where the Work is a model or dataset, the Corresponding
Materials include all components listed in the definition above.

**1.2 Combined Works.** A work that combines Output from a covered Model with
other data or software is a derived work if:
- (a) the Output constitutes a substantial portion of the new work; or
- (b) the new work is a Derived Model; or
- (c) the new work is specifically designed to replace or augment the covered
      Model or Dataset.

**1.3 API/SaaS Use.** Using a covered Model through an Inference Service
constitutes propagation of the Work.  The operator of the Inference Service
must comply with all disclosure obligations in section 12.

### 2. Source Code and Materials.

The "source code" for data-oriented works means:

- **For Datasets**: The complete raw data in its original format, all
  annotations, all preprocessing scripts, and all tools required to regenerate
  the exact dataset from its original sources.

- **For Models**: The complete model architecture definition, all trained
  weights and parameters, all training and evaluation code, all
  hyperparameter configurations, and all experimental logs.

- **For Training Pipelines**: All scripts, configuration files, environment
  specifications, and documentation required to reproduce the training process
  exactly.

### 3. Basic Permissions.

All rights granted under this License are conditional upon continued compliance
with its terms.

You may run, copy, and modify the Work for any lawful non-commercial purpose,
provided that you comply with all disclosure obligations.

Fair use, fair dealing, and academic fair use exceptions are preserved to the
extent recognized by applicable law.  If your use would be considered fair use
under copyright law, it is also permitted under this License even if it would
otherwise be a modification.

### 4. Dataset Attribution and Provenance.

**4.1 Attribution.** Any public use or publication of results obtained from a
covered Dataset must include proper attribution to the original dataset and
its authors.

**4.2 Provenance Log.** If you modify a Dataset, you must maintain a provenance
log that records:
- Every modification made, including timestamps;
- The source of any new data added;
- The rationale for each modification;
- The identity of the person who made the modification.

**4.3 Derived Datasets.** Any Dataset derived from a covered Dataset must be
licensed under this License and must include a complete provenance log linking
back to the original.

### 5. Conveying Verbatim Copies.

You may convey verbatim copies of the Work as you received it, provided you
keep intact all notices, include a copy of this License, and provide a publicly
accessible URL from which the complete Corresponding Materials can be retrieved
at no charge for at least five years.

### 6. Conveying Modified Versions.

You may convey a modified version of the Work under the terms of section 5,
provided that:

- **a)** The work carries prominent notices stating that you modified it.
- **b)** The work is licensed under this License.
- **c)** You license the entire modified work under this License.
- **d)** You update the provenance log (for Datasets) or experimental log
  (for Models) to reflect all changes.
- **e)** You provide the complete Corresponding Materials for the modified
  work.

### 7. Derived Models.

Any Derived Model must be licensed under this License.  When you distribute a
Derived Model, you must include:

- **a)** The complete Corresponding Materials for the Derived Model;
- **b)** A pointer to the original Work from which it was derived;
- **c)** A description of the derivation process (fine-tuning data,
  distillation procedure, etc.);
- **d)** The complete derivation pipeline (scripts, configurations, data).

### 8. Conveying Non-Source Forms.

You may convey non-source forms (compiled models, preprocessed datasets,
binary formats) only if you also convey the Corresponding Materials in one
of these ways:

- **a)** On a durable physical medium;
- **b)** Through a publicly accessible network server, at no charge;
- **c)** Through a written offer valid for at least three years.

### 9. Additional Terms.

Permitted additional terms are limited to:
- a) Disclaiming warranty or limiting liability.
- b) Requiring preservation of attribution notices.
- c) Requiring citation in academic publications.
- d) Prohibiting use for specified harmful purposes (ethical use restrictions).

### 10. Termination and Cure.

Any violation of this License automatically terminates your rights under this
License.

**Cure Period**: If this is your first documented violation, and you cure the
violation within 60 calendar days of receiving written notice, your rights are
reinstated.  Continued use of a Derived Model without complying with disclosure
obligations is not subject to cure.

### 11. Patents.

Each contributor grants a non-exclusive, worldwide, royalty-free patent license
under their essential patent claims that read on the Work.  Patent litigation
against any party regarding the Work terminates all rights under this License.

### 12. Remote Network Interaction and Inference Services.

**12.1 Model Access.** If you provide access to a covered Model through an
Inference Service, whether for free or for a fee, you must:

- **a)** Offer the complete Corresponding Materials at no charge through a
  publicly accessible network server;
- **b)** Provide a prominent notice (in the API response, web interface, or
  terms of service) that the service is powered by a model under this License
  and where to obtain the Corresponding Materials;
- **c)** Include the Corresponding Materials URL in every API response header
  (`X-Model-Source`).

**12.2 Output Disclosure.** You must log all API inputs and outputs in a
publicly accessible archive, unless doing so would violate applicable privacy
laws, in which case you must provide anonymized logs and a detailed explanation
of the redaction process.

**12.3 Derived Model Services.** If you provide an Inference Service powered
by a Derived Model, the obligations of this section apply to the Derived Model
as well.

### 13. Ethical Use Restriction (Optional).

The copyright holder may designate specific prohibited use cases, including
but not limited to:
- Surveillance systems that violate human rights;
- Autonomous weapons systems;
- Systems that make automated decisions about credit, employment, or housing
  without human review.

If such restrictions are designated, they must be listed in a separate
`ETHICAL_USE.md` file distributed with the Work.

### 14. Revised Versions.

The copyright holder may publish revised versions of this License.  You may
use the Work under any version of this License that the Work's copyright holder
designates.

### 15. Disclaimer of Warranty.

THERE IS NO WARRANTY FOR THE WORK, TO THE EXTENT PERMITTED BY APPLICABLE LAW.
DATASETS AND MODELS ARE PROVIDED "AS IS" WITHOUT WARRANTY OF ACCURACY,
COMPLETENESS, OR FITNESS FOR A PARTICULAR PURPOSE.

### 16. Limitation of Liability.

IN NO EVENT SHALL ANY COPYRIGHT HOLDER BE LIABLE FOR ANY DAMAGES WHATSOEVER
ARISING OUT OF THE USE OR INABILITY TO USE THE WORK, INCLUDING DAMAGES FROM
MODEL OUTPUT, DATA INACCURACIES, OR ALGORITHMIC BIAS.

### 17. Interpretation.

If any provision of this License is held to be unenforceable, the remaining
provisions shall remain in full force and effect.

**END OF TERMS AND CONDITIONS**


## How to Apply These Terms

Attach the following notice to every data file, source file, and model
checkpoint, and include the full license text as `LICENSE`:


<one line to give the work's name>
Copyright (C) <year> <name of author>

This work is free: you can redistribute it and/or modify it under the
terms of the Strong Affero General Public License for Data, version 1.0.
Models, datasets, and training pipelines are included.  There is NO WARRANTY;
not even for MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
Full terms: <URL to license text>.


Ensure that any Inference Service powered by this work provides a prominent
`X-Model-Source` header or equivalent notice pointing to the Corresponding
Materials.
