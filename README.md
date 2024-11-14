# Genome Analysis of *Prevotella pleuritidis*: MAGs and Pangenome Study

## Overview
This project investigates 30 *Metagenome Assembled Genomes* (MAGs) from the species *Prevotella pleuritidis*. The goal is to provide both qualitative and quantitative insights into the genomic content of this species and explore its pangenome to assess its genetic variability.

### Objectives
- Analyze the quality of MAGs and determine their completeness.
- Examine the genetic content of *P. pleuritidis*, including core and accessory genes within its pangenome.
- Conduct a phylogenetic analysis to correlate the MAGs with patient metadata.

## Methodology
### Data Collection
The genomic data used in this project were collected from clinical samples of patients with various oral conditions, including peri-implantitis, mucositis, and healthy controls. These samples were sequenced using advanced sequencing technologies, and MAGs were assembled to represent the genomes of *P. pleuritidis*.

### Genomic Analysis
A combination of bioinformatics tools was used for genome annotation, gene prediction, and pangenome analysis. This analysis focused on identifying core genes (present in the majority of strains) and accessory genes (present in a smaller subset), as well as conducting phylogenetic analysis.

## Results

### MAG Quality
- **High-quality genomes** (completeness >90%, contamination <5%): 16/30
- **Medium-quality genomes** (completeness between 50% and 90%): 14/30
- **Low-quality genomes** (completeness <50% or contamination >5%): 0/30

**Statistics:**
- Average completeness: 86.5%
- Average contamination: 0.754%
- Average GC content: 0.452 ± 0.003
- Average genome size: ~2.1 Mb
- Average number of predicted genes: ~2059

### Genomic Annotation
The MAGs were annotated to detect 54,103 proteins, of which 25,013 were known proteins, and 29,090 were hypothetical proteins. A significant portion (about 54%) of the proteome consisted of hypothetical proteins, which could potentially be further explored through experimental validation.

### Pangenome Analysis
The pangenome of *P. pleuritidis* consists of 5336 genes, including 764 core genes (present in at least 90% of strains) and 4572 accessory genes. The core genome constitutes about 14% of the total genes, indicating that *P. pleuritidis* has extensive genetic flexibility, characteristic of open pangenomes.

### Phylogenetic Analysis
Phylogenetic trees were constructed using core and accessory genes. The analysis revealed two main subtrees, with further subdivisions into clades. Metadata associated with each patient, such as sex, BMI, age, smoking status, and oral condition, were included to explore potential correlations. However, no significant correlation was observed due to the small dataset size.

## Key Findings
- *P. pleuritidis* exhibits high genetic variability, as indicated by the large proportion of accessory genes in its pangenome.
- Hypothetical proteins make up a substantial part of the proteome and may have unexplored functions.
- While phylogenetic analysis suggested some correlations between MAGs and patient metadata, the results were statistically insignificant due to the limited number of samples.

## Conclusions
This project analyzed 30 MAGs of *Prevotella pleuritidis*, revealing extensive genetic plasticity and the need for further studies to fully characterize the genetic content of this species. The role of *P. pleuritidis* in the oral microbiome, particularly during inflammatory conditions, remains unclear. Future research should focus on identifying the functions of the genes, especially those differentially expressed in strains from various inflammatory states.

## Requirements
- Python 3.8+
- Required packages: pandas, biopython, matplotlib, seaborn, etc.
- R (for pangenome and phylogenetic analysis)
