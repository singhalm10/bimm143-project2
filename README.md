# bimm143-project2

## Assessing Differences in the CA2 Hippocampal Region through the PTPN5 gene

Meenakshi Singhal
BIMM 143 Spring 2022, Project 2


### Scientific Question:
How has PTPN5--a marker gene for the CA2 hippocampus region--been evolutionarily conserved between mice, humans, and the common marmoset?

### Hypothesis:
If sequence alignment reveals differences between mice, humans, and the common marmoset for the PTPN5 marker gene of the CA2 hippocampus region, then homology modeling and sequence logos of this PTPN5 protein will further elucidate evolutionary relationships between the three species.

## Bioinformatics procedures 

### Database 1:
NCBI Nucleotide search

### Method 1:
Pairwise sequence alignment

### Analysis 1:
Heatmap

### Database 2: 
PDB

### Method 2:
Homology Modeling and Structural Bioinformatics

### Analysis 2:
3d protein measurements 

### Method 3:
Multiple sequence alignment

### Analysis 3:
Sequence logos

## Files:

- MS_Project 2.ipynb: Jupyter notebook of code
- MS_Project 2.html: html file of code

1. **Sequence Alignment** 
- mouse_gene.fasta.txt: FASTA file from NCBI of coding region of PTPN5 protein in mice; used during sequence alignment 


- hum_gene.fasta.txt: FASTA file from NCBI of coding region of PTPN5 protein in humans; used during sequence alignment 


- marmoset_gene.fasta.txt: FASTA file from NCBI of coding region of PTPN5 protein in common marmoset; used during sequence alignment 

2. **Homology Modeling**
- 2bv5.cif: file to load and visualize 2bv5 (human) PTN5 protein with nglviewer
- 6h8s.cif: file to load and visualize 6h8s (murine) PTN5 protein with nglviewer


- 2bv5.pdb: PDB file to visualize 2bv5 (human) PTN5 protein in Pymol
  - used as template file in homology modeling
- 6h8s.pdb: PDB file to visualize 6h8s (murine) PTN5 protein in Pymol
- swiss_model.pdb: PDB file to visualize homology protein made via SWISS Model in Pymol
- swiss_model.pdb.cif: same file as above, in CIF format to read into nglviewer

- rcsb_pdb_2BV5.fasta: FASTA file of amino acid sequence for 2bv5 (human) PTN5 protein, from RCSB database
- rcsb_pdb_6H8S.fasta: FASTA file of amino acid sequence for 6h8s (murine) PTN5 protein, from RCSB database
    - used as target sequence in homology modeling

3. **Multi-Sequence Alignment**
- multiseq.fasta: FASTA file of aligned PTPN5 nucleotide sequences for human, mouse, and common marmoset (generated through MAFFT)

#### Images: 
- swiss_model_quality_estimate.png: an plot showing the estimated quality of each modeled residue in the new murine PTPN5 structure
- swiss_model_ramachandran.png: an image of the Ramachandran plot of the homology structure of murine PTPN5, developed via SWISS model
- swiss_structure.png: an image of the homology structure of murine PTPN5

- swiss_mouse.png: image of SWISS model structure aligned with mouse PTPN5 protein in PyMOL
- swiss_hum.png: image of SWISS model structure aligned with human PTPN5 protein in PyMOL
