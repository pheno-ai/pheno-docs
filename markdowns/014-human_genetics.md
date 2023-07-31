# Human genetics (Gencove) 

The Human Phenotype Project collects genomic variation data on all its participants. The genomic data together with the Human Phenotype Project  deep-phenotypes allows to investigate the progression of disease, and to explore personalized treatments. We genotype millions of positions by low-pass sequencing combined with imputation using gencove platform technologies. Genotype imputation is a process of statistically inferring unobserved genotypes using known haplotypes in a population. The performance of Gencove genotype imputation is very high ( accuracy > 98% ) (Wasik et al. 2021). 

### Data availability:
The information is stored in a number of statistics parquet files:<br>
- `human_genetics.parquet`: sample metadata, including QC statistics, paths to PLINK variant files (raw and post-QC), and principal components (PCs).<br>
- `variants_qc.parquet`: variant QC statistics.<br>
- `relationship/relationship_ibs.txt`: IBS calculated by PLINK for pairs of participants.<br>
- `relationship/relationship_king.tsv`: King kinship coefficients for pairs of participants.<br>
- `pca/pca.parquet`: a PLINK file containing  principal components.<br>
- `pca/pca_loadings.tsv`: a PLINK file containing principal component loadings calculated.<br>