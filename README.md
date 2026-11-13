# Escherichia coli K-12 Genome Analysis

This project explores the genome of *Escherichia coli* K-12 using Illumina paired-end sequencing data (SRA accession: [SRR6436961](https://www.ncbi.nlm.nih.gov/sra/SRR6436961)).

The workflow covers the main steps of bacterial genome analysis, from raw sequencing data to genome assembly and annotation.

## Workflow

| Step | Tools |
|------|-------|
| Quality control | FastQC, fastp |
| Genome assembly | SPAdes, Unicycler |
| Assembly evaluation | QUAST, custom Perl script |
| Genome annotation | Prokka, RAST |
| Functional analysis | Identification and annotation of genes and proteins |

## Goal

Assemble and characterize the bacterial genome while gaining practical experience in NGS data processing, genome assembly, and bioinformatics analysis.

## Data

- **Organism:** *Escherichia coli* K-12
- **Platform:** Illumina (paired-end)
- **Accession:** SRR6436961

## Requirements

- FastQC
- fastp
- SPAdes
- Unicycler
- QUAST
- Perl
- Prokka
- RAST (web server)

## Author

Sebastian Zapata Balanta