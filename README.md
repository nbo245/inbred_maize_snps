# inbred_maize_snps
The contents of this repository document the genomic loci associated with phenotypic traits associated with maize stalk lodging resistance.  Mark snps were parsed from https://pubmed.ncbi.nlm.nih.gov/36705476/.

snp_markers_with_p_value_below_0.001.csv: csv with all marker snps associated with any of 8 phenotypic traits associated with stalk lodging resistance.
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


