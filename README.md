# Genome Exploration II — *Mobula birostris*
*

## Project Overview

This project explores the basic genome structure and sequence characteristics of the giant oceanic manta ray (Mobula birostris) genome using Galaxy. The analysis was performed using a genome assembly obtained from NCBI and included basic assembly statistics, sequence-length filtering, ORF prediction, and extraction of a specific genomic region.
## Species and Genome Information

- **Species:** *Mobula birostris* (Giant oceanic manta ray)
- **NCBI Assembly Accession:** GCF_030028105.1
- **Assembly Level:** Chromosome
- **Genome Source:** NCBI
- **FASTA file:** `GCF_030028105.1_sMobBir1.hap1_genomic`
- **Approximate file size:** 1.1 GB

## Objective

The objective of this project was to examine the basic structure of the Mobula birostris genome assembly using Galaxy. The analysis focused on assembly statistics, sequence-length distribution, the effect of filtering short sequences, extraction of a selected genomic region, and identification of possible open reading frames (ORFs).
## Tools and Main Steps

1. **FASTA Statistics** — obtained the main assembly statistics, including total length, sequence count, N50, L50, and GC content.
2. **Compute Sequence Length** — calculated the length of each individual sequence.
3. **Sort** — arranged the sequences based on their length.
4. **Filter Sequences by Length** — removed sequences shorter than 10 kb using a ≥10 kb filter.
5. **FASTA Statistics** — generated assembly statistics for the filtered dataset.
6. **getorf** — detected potential open reading frames (ORFs) within the selected sequence.

   
