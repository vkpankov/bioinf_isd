## Identification of tissue-specific immunosuppressive domains in the human genome

### Project objectives

1. Scan a latest version of human proteome with the ISDTool 2.0 utility
2. Preprocess an input file with a description of hypothetical immunosuppressive peptides and obtain FASTA file with sequences of this peptides
3. Search peptide sequences in a six-frame genome translation database
4. Perform tissue-specific analysis of found sequences using transcriptome databases

### Methods and results
1. Peptide sequences were aligned to six-frame genome translation database in two ways: using local alignment with heuristics and using HMM model. The transeq utility was used to translate the genome. The Exonerate tool was used for local alignment of peptide sequences. The HMMER tool was used to build HMM models (separatly by tissue types) and align them to transcriptome. 
2. 100% matches were found for two sequences
3. Tissue specificity not detected. ARCHS4 database was used for differential expression analysis.

### References
1. ftp://ftp.ensembl.org/pub/release-81/fasta/homo_sapiens/
2. exonerate: Slater GS and Birney E (2005) Automated generation of heuristics for biological sequence comparison. BMC Bioinformatics 6:31; doi: 10.1186/1471-2105-6-31
3. HMMER v.3.3: hmmer.org
4. https://www.proteinatlas.org/ 
5.Lv, Hongqiang, et al. "ISDTool 2.0: A computational model for predicting immunosuppressive domain of retroviruses." Journal of theoretical biology 360 (2014): 78-82.
6. Blinov, V.M. & Zverev, Vitaly & Krasnov, George & Filatov, Felix & Shargunov, A.V.. (2017). Viral component of the human genome. Molekuliarnaia biologiia. 51. 240-250. 10.7868/S0026898417020069.
7. Lachmann A, Torre D, Keenan AB, Jagodnik KM, Lee HJ, Wang L, Silverstein MC, Ma’ayan A. Massive mining of publicly available RNA-seq data from human and mouse. Nature Communications 9. Article number: 1366 (2018), doi:10.1038/s41467-018-03751-6
