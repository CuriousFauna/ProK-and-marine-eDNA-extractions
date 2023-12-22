# ProK-and-marine-eDNA-extractions

This is a repository for code and data used in the analysis of the manuscript entitled: "Proteinase K is not essential for marine eDNA metabarcoding".

## Fastq Sequences
Fastq files were submitted to NCBI as "Bioproject PRJNA1011351". You can type in "PRJNA1011351" into the SRA dropdown to obtained the sequences. 

There are 18 files listed. The demultiplexed fastq files are named P1-P21. There are two fastq files per samples, one forward and one reverse. 
The ProK quantities that correspond to the file names are in the metadataProK.csv file located in the Data Folder.

Sequences were processed using a modified version of the eDNAFlow pipeline (https://zenodo.org/records/8278074).

The raw pipeline output is the "proK_eDNAFlow_Output.csv" file located in the Data Folder

## Data and R Code

All data and R code used to obtain the resultes are presented in the Data and R Code folders. The R code is presented in a quarto file. R packages needed to process the data are provided in the respective heading of each R File.
