# RNA-seq

RNA-seq Data Analysis Pipeline

Overview
This repository contains a complete RNA-seq data analysis workflow performed on paired-end sequencing data. The pipeline includes quality control, read trimming, genome alignment, post-alignment processing, gene quantification, and differential expression analysis.

The workflow was implemented on a high-performance computing (HPC) cluster using SLURM job scheduling and standard bioinformatics tools.

Workflow Summary
Raw FASTQ files
        ↓
Fastp (quality control & trimming)
        ↓
STAR (genome indexing & alignment)
        ↓
BAM processing (duplicate removal & filtering)
        ↓
BigWig generation (coverage visualization)
        ↓
FeatureCounts (gene-level quantification)
        ↓
DESeq2 (differential expression analysis)
