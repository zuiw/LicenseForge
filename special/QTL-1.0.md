# Quantization License, Version 1.0 (QTL-1.0)

**Copyright (C) 2026 [Your Name or Organization]**

A license addressing quantized AI models, clarifying whether quantized
weights are derivative works and what obligations apply to quantization
distribution.

## Preamble

Quantization transforms model weights from high-precision (FP16, FP32) to
lower-precision formats (INT8, INT4, NF4, etc.).  The FTL clarifies that
quantized weights are derivative works of the original model, but provides
a streamlined compliance path: as long as the quantization method is fully
documented and reproducible, and the original model license is preserved,
quantized models may be freely distributed.

## TERMS AND CONDITIONS

### 0. Definitions.

"This License" refers to version 1.0 of the Quantization License (QTL-1.0).

"The Model" means the model (weights, architecture, and configuration)
licensed under this License.

"Quantization" means any process that converts Model weights from a higher
bit precision to a lower bit precision, including INT8, INT4, NF4, FP8,
FP4, binary, ternary, and any other reduced-precision format.

"Quantized Model" means a model produced by applying Quantization to the
Model.

"Lossy Quantization" means Quantization where the quantized weights are
not bit-exact reversible to the original weights.

"Lossless Quantization" means Quantization where the original weights can
be exactly reconstructed from the quantized form.

### 1. Model Rights.

You may use, copy, and distribute the Model under the terms specified in
this License.

### 2. Quantization as Derived Work.

Quantization produces a derivative work of the Model.  Subject to the
conditions below, you may create and distribute Quantized Models.

### 3. Conditions for Quantized Distribution.

You may distribute a Quantized Model if:
- **a)** You include a copy of this License with the Quantized Model;
- **b)** You document the Quantization method, calibration data, and
  configuration used;
- **c)** You provide a script or tool to reproduce the Quantization;
- **d)** You document any accuracy or quality metrics comparing the
  Quantized Model to the original Model;
- **e)** You clearly label the Quantized Model with the original Model
  name and quantization method.

### 4. Inference from Quantized Models.

Model Output from a Quantized Model is not subject to this License beyond
the terms that apply to the original Model.

### 5. Multiple Quantization Formats.

You may distribute the same model in multiple quantization formats
simultaneously, provided each format meets the conditions in section 3.

### 6. Termination.

Distribution of Quantized Models without documentation (section 3b-3d)
terminates rights.  A 60-day cure period applies.

### 7. Disclaimer of Warranty.

THE MODEL IS PROVIDED "AS IS", WITHOUT WARRANTY OF QUANTIZATION QUALITY OR
ACCURACY PRESERVATION.

### 8. Limitation of Liability.

IN NO EVENT SHALL THE COPYRIGHT HOLDER BE LIABLE FOR ANY DAMAGES FROM
QUANTIZED MODEL USE.

**END OF TERMS AND CONDITIONS**


## How to Apply These Terms

Include the following notice:

```
<Model name> v<version>
Copyright (C) <year> <author>
Licensed under the Quantization License, version 1.0 (QTL-1.0).
Quantized distribution permitted with documentation and attribution.
Full terms: <URL>.
```
