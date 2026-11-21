# Gut16S Combined Pipeline

Reproducible R/DADA2 workflow for six human gut 16S microbiome studies.

## Contributors and studies
- Vansh: PRJNA687346, PRJNA761547
- Bhavya: PRJNA604466, PRJNA610672
- Krupa: PRJEB20022, PRJNA668251

## Requirements
R 4.5.x, Bioconductor 3.22, DADA2 1.38.0, ggplot2 and Cutadapt 4.7 where required.

## Getting started
Open team_workflow/gut16s-team.Rproj in RStudio. Read team_workflow/START_HERE.md for setup and execution instructions.

## Data
Raw FASTQ files and the SILVA reference database are excluded. The workflow retrieves public sequencing data and verifies checksums.

Cross-study comparisons are descriptive because cohorts, sequencing platforms, primers and processing histories differ.
