## Identification of tissue-specific immunosuppressive domains in the human genome

### Aim
The aim of this project was to identify tissue-specific homologs of the viral immunosuppressive domains in the human cDNA.

### Project objectives
1. to scan a latest version of human proteome with the ISDTool 2.0 
2. to parse putative peptide sequences from an input PDF file into FASTA format
3. to align sequences to human cDNA 
5. to generate HMM models 
4. to estimate if hits are tissue-specific 

### Methods and results
1. Alignment was done in two ways: using local alignment with heuristics and using HMM model. The Exonerate tool was used for local alignment. The HMMER tool was used to build HMM models (separatly by tissue types) and align them to transcriptome. 
2. Two exact matches were found.
3. According to Human Protein Atlas, detected hits aren’t tissue-specific.

### References
1. ftp://ftp.ensembl.org/pub/release-81/fasta/homo_sapiens/
2. exonerate: Slater GS and Birney E (2005) Automated generation of heuristics for biological sequence comparison. BMC Bioinformatics 6:31; doi: 10.1186/1471-2105-6-31
3. HMMER v.3.3: hmmer.org
4. https://www.proteinatlas.org/ 
5. Lv, Hongqiang, et al. "ISDTool 2.0: A computational model for predicting immunosuppressive domain of retroviruses." Journal of theoretical biology 360 (2014): 78-82.
6. Blinov, V.M. & Zverev, Vitaly & Krasnov, George & Filatov, Felix & Shargunov, A.V.. (2017). Viral component of the human genome. Molekuliarnaia biologiia. 51. 240-250. 10.7868/S0026898417020069.
7. Lachmann A, Torre D, Keenan AB, Jagodnik KM, Lee HJ, Wang L, Silverstein MC, Ma’ayan A. Massive mining of publicly available RNA-seq data from human and mouse. Nature Communications 9. Article number: 1366 (2018), doi:10.1038/s41467-018-03751-6
