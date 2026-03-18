# Watershed-Cloud

Scalable implementations pipelines for Watershed, a probabilistic graphical model integrating multiple functional genomics signals to prioritize rare regulatory variants and structural variants. This includes reproducible and efficient analyses of large-scale genomic datasets using modern workflow technologies, demonstrated on publicly available 1000 Genomes Project and matched MAGE RNAseq data.

### Watershed for Single Nucleotide Variants

The pipeline for Watershed on single nucleotide variants resides in the [Watershed-SNV](https://app.terra.bio/#workspaces/nccpi-rti-P01-002-JHU-TERRA/Watershed-SNV-MAGE) workspace in the Terra analysis platform powered by BioData Catalyst.

A critical piece of this pipeline is its eponymous [Watershed-SNV annotation workflow](https://dockstore.org/workflows/github.com/schatzlab/Watershed-SNV-WDL/Watershed-SNV:main?tab=info) implemented in WDL and published on Dockstore. (This workflow is already included as part of the workspace). The workflow pulls together multiple functional annotation sources and applies them to the genetic data in a parallel way, taking advantage of cloud compute resources. (DOI: https://doi.org/10.5281/zenodo.19097200)

### Watershed for Structural Variants

The pipeline for structural variants resides in the [Watershed-SV](https://app.terra.bio/#workspaces/nccpi-rti-P01-002-JHU-TERRA/Watershed-SV-MAGE) Terra workspace, and contains the associated [Watershed-SV annotation workflow](https://dockstore.org/workflows/github.com/jasonbhn/Watershed-SV/Watershed-SV:WDL?tab=info). (DOI: https://doi.org/10.5281/zenodo.19097299)
