# Notebook of RNA-Seq analysis using DIGGER

Applying DIGGER mode: network-level analysis to the RNA-seq data from The Cancer Genome Atlas pan-cancer dataset. Using the structure annotation of isoforms and their expression level, DIGGER constructs a condition-specific PPI.


## Data Sources
- The transcript expressions using RNAseq were obtained from [the Cancer Genome Atlas pan-cancer dataset](https://xenabrowser.net/datapages/). 

- The [BioMart](https://www.ensembl.org/biomart/martview) tool was used to annotate and to map genes, transcripts and proteins.

- [BioGRID](https://thebiogrid.org/): The protein interactions database  was used to generate the PPI.pkl file.


- [3did](https://3did.irbbarcelona.org/) and [DOMINE](https://3did.irbbarcelona.org/): two domains interactions databases  were used to generate the DDI.pkl file.



## For more Details check out DIGGER 
Web tool: https://exbio.wzw.tum.de/digger/

Github Link: https://github.com/louadi/DIGGER


# Dependencies

The notebook requires the following libraries:


[NetworkX ](https://networkx.github.io/)


[pandas](https://pandas.pydata.org/)



## Cite

If you use DIGGER, please cite:


Zakaria Louadi, Kevin Yuan, Alexander Gress, Olga Tsoy, Olga V Kalinina, Jan Baumbach, Tim Kacprowski, Markus List, DIGGER: exploring the functional role of alternative splicing in protein interactions, Nucleic Acids Research, , gkaa768, https://doi.org/10.1093/nar/gkaa768

