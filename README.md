# Human fetal pancreas development
### Olaniru et al manuscript: Single cell transcriptomic and spatial landscapes of the developing human pancreas Cell Metabolism <https://doi.org/10.1016/j.cmet.2022.11.009>


This repository contains the scripts used to explore the single cell RNA-seq and spatial transcriptomics datasets of the developing human pancreas presented in **Olaniru et al (2023): Single cell transcriptomic and spatial landscapes of the developing human pancreas. Cell Metab 35:184-199** 

- The scRNA-seq data were from 7 time points (12, 13, 14, 15, 18, 19 and 20 PCW) but we combined it with data from (Yu et al., 2021 <https://www.nature.com/articles/s41422-021-00486-w>) to extend the timepoints to 10 (8 -20PCW). For our scRNA-seq, we used cell hashing to pull multiple pancreases (3 at a time from different timepoints) in a single run to reduce costs and minimise the impact of batch effects, we then de-multiplex them after sequencing. 
- 10x Visium spatial transcriptomics data were from 12, 15, 18 and 20PCW. 
- We combined the scRNAseq and visium data to resolve the spatial landscape of the developing human pancreas.
#### Datasets
Raw data (FASTQ and metadata) can be accessed on GEO browser with ascession numbers GSE197064 and GSE197317.

### The following analyses are included in this repository :
1. Integration and analysis of multiple scRNAseq data
2. Monocle 3, time-series and in situ pseudotime trajectory inference
3. Analysis of spatial transcriptomics data 
4. Integration of scRNAseq and spatial transcriptomics
