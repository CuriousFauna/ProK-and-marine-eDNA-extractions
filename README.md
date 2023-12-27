# ProK and marine eDNA extractions

This is a repository for code and data used in the analysis of the manuscript entitled: "Proteinase K is not essential for marine eDNA metabarcoding".

## Fastq Sequences
Fastq files were submitted to NCBI as "Bioproject PRJNA1011351". You can type in "PRJNA1011351" into the SRA dropdown to obtained the sequences. 

There are 18 files listed. The demultiplexed fastq files are named P1-P21. There are two fastq files per samples, one forward and one reverse. 
The ProK quantities that correspond to the file names are in the metadataProK.csv file located in the Data Folder.

Sequences were processed using a modified version of the eDNAFlow pipeline (https://zenodo.org/records/8278074).

The raw pipeline output is the "proK_eDNAFlow_Output.csv" file located in the Data Folder

## Data and R Code

All data and R code used to obtain the resultes are presented in the Data and R Code folders. The R code is presented in a quarto file. R packages needed to process the data are provided in the respective heading of each R File. 

In the Data folder there are several files. There's the Zotu fasta output from eDNAFlow (seq_zotus_proK.fasta), the blast results from the eDNAFlow script that compares the taxonomic identity of the top ten hits with at least 97% identity and 100% coverage (seq_blast_Results_proK.csv), the increased taxa resolution file used in the R script (Taxa_better_resolution.csv), the metadata file (metadataProK.csv), the QuBit values file (QuBit_proK.csv), and the resulting data from the pipeline (proK_eDNAFlow_Output.csv).

Note, some of the figures were brought into Adobe Illustrator to move legends, unify colors, and change font types and sizes for publication.
