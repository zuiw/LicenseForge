# Model Registry License, Version 1.0 (MRL-1.0)

**Copyright (C) 2026 [Your Name or Organization]**

A license for model registries, model distribution platforms, and model
catalogs, defining the obligations of model hosts and downstream
consumers.

## Preamble

The MRL addresses the role of model registries in the AI ecosystem.
Registries host, index, and distribute models from multiple authors.  This
license ensures that models distributed through a registry are properly
attributed, that registry metadata is accurate, that model cards are
complete, and that downstream consumers have clear provenance information.

## TERMS AND CONDITIONS

### 0. Definitions.

"This License" refers to version 1.0 of the Model Registry License
(MRL-1.0).

"The Registry" means the model hosting platform, model catalog, or
distribution system licensed under this License.

"Model Entry" means a model listing in the Registry, including model
weights, metadata, documentation, and license information.

"Registry Operator" means the entity operating the Registry.

"Model Author" means the original creator of a model uploaded to the
Registry.

"Model Consumer" means any person or entity that downloads or uses a Model
Entry from the Registry.

### 1. Permissions.

You may use, copy, modify, and distribute the Registry software for any
lawful purpose, subject to the conditions below.

### 2. Registry Obligations.

If you operate the Registry, you must:
- **a)** Display the original license of each Model Entry prominently;
- **b)** Preserve all attribution and copyright notices from Model Authors;
- **c)** Provide provenance information for each Model Entry (author, date,
  source);
- **d)** Support model cards or equivalent documentation;
- **e)** Not misrepresent the origin, authorship, or license of any Model
  Entry;
- **f)** Provide a mechanism for Model Authors to update or remove their
  entries.

### 3. Model Entry Integrity.

You may not modify Model Entries in a way that alters their functionality
or misrepresents their origin.  Permitted modifications are limited to:
- Format conversion (e.g., Safetensors to PyTorch);
- Quantization (documented as such);
- Metadata correction (with Model Author approval).

### 4. Registry Metadata.

The Registry must maintain and expose:
- Original license of each Model Entry;
- Version history and changelog;
- Download counts and usage statistics;
- Security or vulnerability reports.

### 5. Downstream Transparency.

Model Consumers who download from the Registry must be able to:
- View the original license before download;
- Verify the integrity of the download;
- Access the model card and documentation.

### 6. Termination.

Misrepresentation of Model Entry origin or license terminates all rights
with no cure.

### 7. Disclaimer of Warranty.

THE REGISTRY IS PROVIDED "AS IS", WITHOUT WARRANTY OF MODEL QUALITY OR
SAFETY.

### 8. Limitation of Liability.

IN NO EVENT SHALL THE REGISTRY OPERATOR BE LIABLE FOR ANY MODEL BEHAVIOR.

**END OF TERMS AND CONDITIONS**


## How to Apply These Terms

Include the following notice:

```
<Registry name>
Copyright (C) <year> <author>
Licensed under the Model Registry License, version 1.0 (MRL-1.0).
Model author attribution and license preservation required.
Full terms: <URL>.
```
