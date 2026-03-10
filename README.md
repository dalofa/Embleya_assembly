# Special course: Evolution of Secondary Chromosomes in Bacteria

### Suggested intial workflow
- Assembly with Flye
- QC1: Inspect with Bandage to check completeness/topology
- Optional: Polish with Medaka and check if this changes significantly
- Annotate with Bakta
- QC2: Run BUSCO (and optionally CheckM)
- Proceed to analysis of enriched proteins

# Relevant Literature
### Assembling good genomes
Note: The quality of ONT (especially homopolymer calling) has improved since the Ryan Wick paper, so in a number of cases Illumina polishing is not nessesary.
- Wick, Ryan R., et al. “Assembling the Perfect Bacterial Genome Using Oxford Nanopore and Illumina Sequencing.” Plos Computational Biology, edited by Francis Ouellette, vol. 19, no. 3, 2023, p. e1010905, https://doi.org/10.1371/journal.pcbi.1010905.

### Evaluating genome completeness
- Simão, Felipe A., et al. “BUSCO: Assessing Genome Assembly and Annotation Completeness with Single-Copy Orthologs.” Bioinformatics, vol. 31, no. 19, 2015, pp. 3210–12, https://doi.org/10.1093/bioinformatics/btv351.
- Wick RR, Schultz MB, Zobel J, Holt KE. Bandage: interactive visualization of de novo genome assemblies. Bioinformatics. 2015 Oct 15;31(20):3350-2. doi: 10.1093/bioinformatics/btv383

### Annotating genomes (bakta is recommended, but prokka will do for the project)
- Schwengers, Oliver, et al. “Bakta: Rapid and Standardized Annotation of Bacterial Genomes via Alignment-Free Sequence Identification.” Microbial Genomics, vol. 7, no. 11, 2021, p. 000685, https://doi.org/10.1099/MGEN.0.000685.
- Torsten Seemann, Prokka: rapid prokaryotic genome annotation, Bioinformatics, Volume 30, Issue 14, July 2014, Pages 2068–2069, https://doi.org/10.1093/bioinformatics/btu153

### Autocycler (consensus genomes) - might not be relevant for the project
- Ryan R Wick, Benjamin P Howden, Timothy P Stinear, Autocycler: long-read consensus assembly for bacterial genomes, Bioinformatics, Volume 41, Issue 9, September 2025, btaf474, https://doi.org/10.1093/bioinformatics/btaf474

### Linear plasmids/chromsomes in Actinomycetes (in case they show up)
- David Faurdal, T.J. Booth, Tilmann Weber, Tue Sparholt Jørgensen, Tying up loose ends: Recovering thousands of missing telomeres from Streptomyces and other Streptomycetaceae genomes, bioRxiv, 2025.10.14.682034, https://doi.org/10.1101/2025.10.14.682034
