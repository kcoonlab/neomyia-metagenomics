# neomyia-metagenomics

### Overview
Comparative genomic analysis of bacterial strains isolated from *Stomoxys* (stable) flies and manure samples collected on a Wisconsin dairy farm. The repository contains code used for analysis of genomic read data and generation of associated figures.

### Availability of Sequence Data
Raw Illumina reads from the 48 manure samples associated with Teseo et al. (2022) are available in the NCBI Sequence Read Archive (https://www.ncbi.nlm.nih.gov/sra) under BioProject accession number PRJNA681986; reads from the 29 fly samples generated in this study are available under BioProject accession number PRJNA911623.

Scripts used for analysis and figure generation are available at forgemia.inra.fr/sapountzis0454medis/Neomyia_microbiome. 


### The following tables are stored in this repository:

**TableS5** - Analysis of commonly shared and unique KOs between selected MAGs. The KOs are listed with their functional category, preferred name, pathway, module assignment, and BRITE hierarchy. KOs are marked as either shared between fly- and manure-selected MAGs (common), unique to fly-selected MAGs (fly-specific), or unique to manure selected MAGs (cow-specific; see column K). 

**TableS7** - Virulence and antimicrobial resistance features identified in cow manure and fly samples. All virulence factors (VFDB) and ARGs (Resfinder) identified are shown with their associated prevalences in each sample type (see subtables A and B). Genes found to be shared or unique to each sample type prior to and after filtering (Figure 3A) are noted in columns D-F. Average CLR abundances in manure and fly samples are shown in columns G and H. CLR abundances are based off counts after filtering to remove genes with >80% zero counts. Statistical differences between CLR transformed abundances were determined using Wilcoxon signed-rank tests (column J) and p-values were adjusted using a Bonferroni correction (column J) based on the total number of comparisons in each group (N= 399comparisons for VFs and 57 comparisons for ARGs). Instances where an identified VF or ARG mapped with >90% coverage are noted in subtables C and D.


### Contact 
Andrew J. Sommer - asommer3@wisc.edu\
Kerri L. Coon - kerri.coon@wisc.edu\
Panagiotis (Panos) Sapountzis - panagiotis.sapountzis@inrae.fr
