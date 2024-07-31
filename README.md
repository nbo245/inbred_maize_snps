# inbred_maize_snps
The contents of this repository document the genomic loci associated with phenotypic traits associated with maize stalk lodging resistance.  Mark snps were parsed from https://pubmed.ncbi.nlm.nih.gov/36705476/.

**snp_markers_with_p_value_below_0.001.csv** : csv with all marker snps associated with any of 8 phenotypic traits associated with stalk lodging resistance.
* Source - the phenotype examined
* SNP - the name of a SNP (chromosome_position)
* CHROM - the chromosome on which the SNP was found
* POS - the bp location of the SNP on a CHROM
* REF - the reference allele
* ALT - the alternative allele
* Effect - the effect calculated in the iteration w/ the lowest p-value of a particular SNP
* SE - the standard error calculated in the iteration w/ the lowest p-value of a particular SNP
* pvalue - the lowest p-value returned for a particular SNP
* RMIP - the RMIP score, a value between 0-1, noting the ratio out of 100 that a SNP was found to be significantly assocaited with a phenotype noted in Source

**paneffect_genes_pvalues.csv** : csv with 8802 consensus genes that were identified within 3 genes of a significant snp in the current study and within 1kb of either of the GWAS atlas' examined.
* Gene ID: The gene id of the linked gene
* Source: The phenotype examined
* SNP: a significantly identified marker SNP
* Rank: a value between 1-3, indicating the ordinal proximity of the gene to a significant SNP
* RMIP: the RMIP score, a value between 0-1, noting the ratio out of 100 that a SNP was found to be significantly assocaited with a phenotype noted in Source
* SNP Proximity: the bp distance between the marker SNP and the linked gene
* Phenotype: The phenoytpe either of the external GWAS atlas' associated with the linked gene
* GWAS_Source: The reference of the association study which identified the gene
* Cross Trait: The number of traits (current study only) the marker SNP was identified in with a p value less than 0.001
* p value: the lowest p value identified in the current study
* Description: The description of the protein coding gene identified

