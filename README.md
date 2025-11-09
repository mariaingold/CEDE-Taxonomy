# CEDE Taxonomy

**Author:** Maria Ingold  
**Project:** MSc Artificial Intelligence (AI) Dissertation, University of Essex Online  
**Title:** *Mapping AI in Media: CEDE Taxonomy-Driven LLM Classification*  
**Version:** 0.4 (2025-11-09)  
**Repository:** [https://github.com/mariaingold/CEDE-Taxonomy](https://github.com/mariaingold/CEDE-Taxonomy)  
**Copyright:** © 2025 Maria Ingold  

## Overview

The **CEDE Taxonomy** (Create, Enrich, Deliver, Engage) provides a structured framework for classifying AI in media product use cases across production, broadcast, and streaming workflows.  

## Citation

All taxonomy references in academic or professional work, please cite as:  
Ingold, M. (2025). *CEDE Taxonomy for AI in Media (v0.4)*. Available at: [https://github.com/mariaingold/CEDE-Taxonomy](https://github.com/mariaingold/CEDE-Taxonomy)  

## Files

- `cede_taxonomy.yaml` : CEDE Taxonomy (version: 0.4).  
- `README.md` : Documentation and usage guidance.  
- `LICENSE.md` : Licensing terms (CC BY-NC-ND 4.0 International).  

## Release Notes

This version (`cede_taxonomy.yaml`, v0.4) represents the initial public release supporting the MSc AI dissertation.  
This release is made **public for academic transparency** and **non-commercial use only** as per the licence.  

## Format

```yaml
categories:
- label: Category
  key: CATEGORY
  subcategories:

  - label: Subcategory
    key: CATEGORY.SUBCATEGORY
    use_cases:
    - label: Use Case
      key: CATEGORY.SUBCATEGORY.USE_CASE
```

## Examples

```yaml
ENRICH.LOCALISATION_AND_ACCESSIBILITY.AUDIO_TRANSLATION
ENRICH.LOCALISATION_AND_ACCESSIBILITY.DUBBING
ENRICH.LOCALISATION_AND_ACCESSIBILITY.SUBTITLING
ENRICH.LOCALISATION_AND_ACCESSIBILITY.TEXT_TRANSLATION
ENRICH.LOCALISATION_AND_ACCESSIBILITY.TRANSCRIPTION
```

## Governance

The CEDE taxonomy is maintained under change control with oversight by the author to maintain structural validity and intent.  

```yaml
governance:
  change_control:
    review_required: true
    reviewers: ["maria_ingold"]
```

Future versions are likely to introduce collaborative subject matter input through formalised contribution guidelines, but all merges and official releases are subject to review by named reviewers.  

## Contact

**Maria Ingold**  
LinkedIn: [https://www.linkedin.com/in/mariaingold/](https://www.linkedin.com/in/mariaingold/)  

For academic queries, collaboration proposals, or licensing requests beyond licencing terms, please contact via LinkedIn.
