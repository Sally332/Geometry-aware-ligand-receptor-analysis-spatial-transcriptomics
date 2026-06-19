# Geometry-Aware Ligand–Receptor Analysis for Spatial Transcriptomics

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.19476574.svg)](https://doi.org/10.5281/zenodo.19476574)
![Research](https://img.shields.io/badge/type-research%20resource-blue)
![Domain](https://img.shields.io/badge/domain-spatial%20transcriptomics-green)
![Focus](https://img.shields.io/badge/focus-cell--cell%20communication-orange)

A geometry-aware framework for prioritizing biologically meaningful ligand–receptor interactions in spatial transcriptomics.

## Overview

Cell–cell communication analyses frequently identify large numbers of statistically significant ligand–receptor interactions, making it difficult to distinguish biologically meaningful signaling programs from interactions driven by tissue composition or spatial organization alone.

This study introduces a geometry-aware framework that separates interface association from spatial localization and evaluates ligand–receptor interactions using distance-weighted boundary scoring, geometry-preserving null models, and localization-based prioritization metrics.

Applied across multiple tumor microenvironments, the framework reveals conserved and tissue-specific communication programs while providing quantitative measures of spatial constraint.

## Scientific Contributions

- Introduces a geometry-aware framework for ligand–receptor analysis in spatial transcriptomics.
- Separates interface enrichment from spatial localization.
- Implements geometry-preserving permutation-based null models.
- Quantifies ligand–receptor retention around cellular interfaces.
- Prioritizes communication programs using spatial evidence rather than expression alone.
- Reveals a continuum of spatial constraint rather than discrete communication regimes.
- Identifies conserved and tissue-specific signaling programs across tumor types.

## Study Design

The framework was applied to four spatial transcriptomic cancer datasets:

- Breast cancer
- Colorectal cancer (CRC)
- Melanoma
- Pancreatic ductal adenocarcinoma (PDAC)

Each dataset was analyzed using an identical computational workflow to enable direct cross-tissue comparisons.

## Repository Resources

### Manuscript

- `Paper.pdf`

### Publication Figures

- `Figure1_Geometry_Aware_Framework.pdf`
- `Figure2A_Top_Pathways_By_Tissue.pdf`
- `Figure2B_Recurrent_Pathway_Composition.pdf`
- `Figure3A_Observed_vs_Null.pdf`
- `Figure3B_Null_Gap_Distribution.pdf`
- `Figure3C_Effect_Size_vs_Significance.pdf`
- `Figure4A_Boundary_vs_Geometry_Aware_Score.pdf`
- `Figure4B_Retention_Distribution.pdf`
- `Figure4C_Sample_Level_Retention.pdf`
- `Figure5A_Retention_vs_Diffuse_Fraction.pdf`
- `Figure5B_Retention_vs_Null_Gap.pdf`
- `Figure5C_Retention_By_Tissue.pdf`
- `Figure6A_Conserved_Pathway_Retention.pdf`
- `Figure6B_Conserved_Pathway_Composition.pdf`
- `Figure6C_Tissue_Specific_Pathway_Retention.pdf`
- `Figure6D_Global_Regime_Composition.pdf`

## Analysis Modules

| Notebook | Scientific Focus |
|-----------|-----------|
| `breast_cancer_geometry_aware_lr_analysis.ipynb` | Geometry-aware ligand–receptor analysis in breast cancer spatial transcriptomics. |
| `colorectal_cancer_geometry_aware_lr_analysis.ipynb` | Geometry-aware ligand–receptor analysis in colorectal cancer. |
| `melanoma_geometry_aware_lr_analysis.ipynb` | Characterization of geometry-aware cell–cell communication in melanoma. |
| `pdac_geometry_aware_lr_analysis.ipynb` | Analysis of spatially constrained signaling programs in pancreatic ductal adenocarcinoma. |
| `manuscript_figure_generation.ipynb` | Reproduction of publication figures and cross-tissue summaries. |

## Key Findings

- Interface enrichment and spatial localization are distinct properties.
- Strong interface association alone does not establish spatial specificity.
- Geometry-aware refinement substantially changes ligand–receptor prioritization.
- Conserved signaling pathways are deployed under different spatial constraints.
- Tumor communication is better described as a continuum of spatial constraint.

## Reproducibility

All analyses are provided as documented Jupyter notebooks together with publication figures and manuscript resources. The repository is intended as a reproducible research resource for spatial transcriptomics, tumor microenvironment analysis, and cell–cell communication studies.

## Citation

Yepes S. (2026). *Geometry-aware ligand–receptor analysis reveals tumor communication patterns.*

DOI: https://doi.org/10.5281/zenodo.19476574

