
This repository implements an LD-aware Mendelian Randomisation (MR) framework to investigate how fine-mapped genetic variants associated with vigorous physical activity influence gene expression at single-cell resolution across major immune cell types.
Using harmonised exposure data from UK Biobank fine-mapped physical activity SNPs and outcome data from the OneK1K single-cell eQTL/sQTL consortium, the pipeline integrates:

LD-adjusted causal estimation (IVW, Egger, Wald ratio)

Cochran’s Q heterogeneity tests

Steiger directionality filtering

Coloc-ready SNP-level output for downstream Bayesian colocalisation (e.g., coloc.abf())

The workflow enables cell-type–specific causal inference linking physical activity genetics to immune transcriptional pathways implicated in inflammation, DNA repair, and ageing.

Highlights

Fully LD-aware via OpenGWAS or LDlink APIs

Supports all six OneK1K immune subtypes: CD4⁺, CD8⁺, B, NK, monocytes, and dendritic cells

Generates Q-statistics, pleiotropy diagnostics, and directionality assessments

Produces harmonised per-gene SNP-level tables for colocalisation or multi-omic integration
