# Retrieval-Augmented Generation License, Version 1.0 (RAGL-1.0)

**Copyright (C) 2026 [Your Name or Organization]**

A license designed for RAG (Retrieval-Augmented Generation) pipelines,
addressing the interaction between retrieval systems, embedding models,
and generative AI components.

## Preamble

The RAGL addresses the multi-component nature of RAG systems: retrieval
indexes, embedding models, rerankers, generative models, and orchestration
frameworks.  It permits free use and modification while requiring that
retrieved content be properly attributed, that pipeline configurations be
documented, and that retrieved source material be accessible to end users.

## TERMS AND CONDITIONS

### 0. Definitions.

"This License" refers to version 1.0 of the Retrieval-Augmented Generation
License (RAGL-1.0).

"The Pipeline" means the RAG system, including retrieval components,
embedding models, rerankers, generators, prompt templates, and
orchestration code licensed under this License.

"Retrieved Content" means any documents, passages, or data returned by
the retrieval components of the Pipeline.

"Generated Output" means the text, code, or other content produced by the
generative component of the Pipeline.

"Source Attribution" means a clear reference to the original source of
Retrieved Content, including author, title, and location.

### 1. Permissions.

You may use, copy, modify, and distribute the Pipeline for any lawful
purpose, subject to the conditions below.

### 2. Source Attribution.

If the Pipeline is used to generate responses based on Retrieved Content,
the system must:
- **a)** Provide Source Attribution for Retrieved Content used in
  generating responses;
- **b)** Distinguish between Retrieved Content and Generated Output in the
  user interface;
- **c)** Allow users to access the original source material.

### 3. Pipeline Transparency.

If you distribute or operate the Pipeline, you must document:
- **a)** The retrieval source(s) and index configuration;
- **b)** The embedding model and reranker used;
- **c)** The generative model and prompt template;
- **d)** Any filtering, ranking, or re-ranking applied.

### 4. No Hallucination Misrepresentation.

You may not represent Generated Output as factual when the generative
model's confidence is low, unless you clearly label it as potentially
inaccurate.

### 5. Modified Pipelines.

Modified versions of the Pipeline must:
- Maintain the attribution requirements of section 2;
- Document changes to the Pipeline configuration.

### 6. Termination.

Failure to provide Source Attribution for Retrieved Content terminates
rights.  A 30-day cure period applies.

### 7. Disclaimer of Warranty.

THE PIPELINE IS PROVIDED "AS IS", WITHOUT WARRANTY OF RETRIEVAL ACCURACY
OR GENERATION QUALITY.

### 8. Limitation of Liability.

IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR ANY GENERATED OUTPUT.

**END OF TERMS AND CONDITIONS**


## How to Apply These Terms

Include the following notice:

```
<RAG Pipeline name> v<version>
Copyright (C) <year> <author>
Licensed under the Retrieval-Augmented Generation License, version 1.0
(RAGL-1.0).  Source attribution required.
Full terms: <URL>.
```
