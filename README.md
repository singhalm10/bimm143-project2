# bimm143-project2
BIMM 143 Spring 2022, Project 2


### Scientific Question:
How has PTPN5--a marker gene for the CA2 hippocampus region--been evolutionarily conserved between mice, humans, and the common marmoset?

### Hypothesis:
If sequence alignment reveals differences between mice, humans, and the common marmoset for the PTPN5 marker gene of the CA2 hippocampus region, then homology modeling and sequence logos of this PTPN5 protein will further elucidate evolutionary relationships between the three species.

### Database 1:
NCBI Nucleotide search

### Method 1:
Pairwise sequence alignment

### Database 2: 
SWISS Model

### Method 2:
Homology Modeling and Structural Bioinformatics

#### potentially adding PCA analysis of RNAseq data (if time)

### Database 3: NCBI (GEO)
- Murine RNAseq data GEO, from Cembrowski et al., Elife 2016: https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?token=adsveykeprejbej&acc=GSE74985
- Human RNAseq data GEO, from Ahyan et al., Neuron 2021: https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE160189

### Analysis Methods:
Heat map, PCA, 3D protein measurements

## Files:

- MS_Project 2.ipynb: Jupyter notebook of current coding progress
- MS_Project 2.html: html file of current coding progress

1. Sequence Alignment 
- mouse_gene.fasta: contains nucleotide sequence for murine RGS14  (https://www.ncbi.nlm.nih.gov/nuccore/NC_000079.7?report=fasta&from=55517269&to=55532504)
- human_gene.fasta: contains nucleotide sequence for human RGS14  (https://www.ncbi.nlm.nih.gov/nuccore/NM_006480.5?report=fasta&log$=seqview)

2. Homology Modeling
- mouse_swiss.fasta: contains amino acid sequence for mouse RGS14 protein (https://swissmodel.expasy.org/repository/uniprot/P97492)
- human_swiss.fasta: contains amino acid sequence for human RGS14 protein (https://swissmodel.expasy.org/repository/uniprot/O43566)
