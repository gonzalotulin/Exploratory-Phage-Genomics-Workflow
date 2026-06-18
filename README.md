# Exploratory Phage Genomics Workflow

## Overview

This project presents a small, reproducible bioinformatics workflow developed using Biopython and publicly available GenBank records.

The workflow is centered on **Garey24**, a bacteriophage isolated through the SEA-PHAGES program. During my work as a microbiology instructor at the Universidad Nacional de Rosario, I supervised undergraduate students in phage isolation, purification, and characterization. From 43 environmental soil samples, 24 phage-positive isolates were obtained, and Garey24 was subsequently selected for sequencing and annotation.

Using Garey24 as a starting point, this notebook demonstrates how publicly available phage genomes can be retrieved, screened, compared, and visualized through a simple automated workflow.

## Workflow

The notebook implements four main steps:

1. **Automated Genome Acquisition**

   * Retrieval of phage genomes directly from the NCBI GenBank database using Biopython.

2. **Annotation-Based Screening**

   * Identification of annotations associated with lysogeny, virulence, toxins, resistance genes, and other potentially undesirable features.

3. **Comparative Protein Analysis**

   * Extraction of a conserved structural marker protein.
   * Pairwise protein alignment using BLOSUM62.
   * Generation of a sequence identity matrix.

4. **Data Visualization**

   * Heatmap visualization of pairwise sequence identity.
   * Hierarchical clustering of phages based on similarity profiles.

## Technologies

* Python
* Biopython
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy

## Example Output

The workflow identifies groups of closely related phages based on a conserved structural marker protein and visualizes similarity relationships through clustered heatmaps.

## Disclaimer

This project is intended as an exploratory bioinformatics exercise and portfolio piece. 
