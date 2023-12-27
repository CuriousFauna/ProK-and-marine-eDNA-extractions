# ProK and marine eDNA extractions

This is a repository for code and data used in the analysis of the manuscript entitled: "Proteinase K is not essential for marine eDNA metabarcoding".

## Fastq Sequences
Fastq files were submitted to NCBI as "Bioproject PRJNA1011351". You can type in "PRJNA1011351" into the SRA dropdown to obtained the sequences. 

There are 18 files listed. The demultiplexed fastq files are named P1-P21. There are two fastq files per samples, one forward and one reverse. 
The ProK quantities that correspond to the file names are in the metadataProK.csv file located in the Data Folder.

Sequences were processed using a modified version of the eDNAFlow pipeline (https://zenodo.org/records/8278074).

The raw pipeline output is the "proK_eDNAFlow_Output.csv" file located in the Data Folder

## Data and R Code

All data and R code used to obtain the results are presented in the Data and R Code folders.

The Data folder has several files. There's the Zotu fasta output from eDNAFlow (seq_zotus_proK.fasta), the blast results from the eDNAFlow script that compares the taxonomic identity of the top ten hits with at least 97% identity and 100% coverage (seq_blast_Results_proK.csv), the increased taxa resolution file used in the main R script (ProK_taxa_resolution.csv), the metadata file (metadataProK.csv), the QuBit values file (QuBit_proK.csv), and the resulting data from the pipeline (proK_eDNAFlow_Output.csv).

The R folder contains the manuscript R code targeting metazoans and macroalgae (ProKAnalysis.qmd), the source code to produce VennBarPlot graph (SourceVenn.R) and the appendix code (ProK_All_Taxa.qmd). The ProK_All_Taxa.qmd was provided per a reviewers request to provide the analyses based on all identified domains and kingdoms with no additional taxonomic collapsing rather than on just metazoans and macroalgae targets. The results do not change.

Note, some of the figures were brought into Adobe Illustrator to move legends, unify colors, and change font types and sizes for publication.
