# Attribution and provenance

## Teaching material

This repository is an educational derivative of:

- **Original repository:** [aghozlane/debruijn-tp](https://github.com/aghozlane/debruijn-tp)
- **Original author:** Amine Ghozlane
- **Institution named in the source:** Université Paris Diderot
- **Material reused:** repository structure, function signatures, docstrings, automated tests, small fixtures, and example dataset
- **Original software license notice:** GNU General Public License, version 3 or later

The original Git history has been preserved so that authorship and the evolution of the teaching material remain inspectable.

## Student implementation

Gaith Korchid completed the course scaffold in commit [d6f36b5](https://github.com/Gaith2000korchid/debruijn-genome-assembler/commit/d6f36b5e917a7fb369372596b83004fa20102f70).

The implementation added the core logic for FASTQ parsing, k-mer counting, graph construction and simplification, source/sink discovery, contig generation, FASTA export, and command-line execution. It also added small read subsets and an expected FASTA fixture.

The later `portfolio-cleanup` work documents provenance, removes personal contact details, declares dependencies, and repairs graph-drawing imports. It does not claim ownership of the upstream teaching scaffold or tests.

## Biological data

- **Reference:** Enterovirus A71, BrCr strain
- **GenBank accession:** [U22521](https://www.ncbi.nlm.nih.gov/nuccore/U22521)
- **Read simulator:** ART; Huang et al., *ART: a next-generation sequencing read simulator*, Bioinformatics (2012), [doi:10.1093/bioinformatics/btr708](https://doi.org/10.1093/bioinformatics/btr708)
- **Data type:** viral reference sequence and simulated sequencing reads
- **Privacy:** no participant-level or confidential clinical data

Third-party data remain subject to the terms of their original sources.
