# RNA-seq Data Analysis Pipeline

This repository contains a complete RNA-seq data analysis workflow performed on paired-end sequencing data. The pipeline includes quality control, read trimming, genome alignment, post-alignment processing, gene quantification, and differential expression analysis.

The workflow was implemented on a high-performance computing (HPC) cluster using SLURM job scheduling and standard bioinformatics tools.

Workflow Summary
1. Raw FASTQ files
2. Fastp (quality control & trimming)
3. STAR (genome indexing & alignment)
4. BAM processing (duplicate removal & filtering)
5. BigWig generation (coverage visualization)
6. FeatureCounts (gene-level quantification)
7. DESeq2 (differential expression analysis)
