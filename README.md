# BIMM-143-Python-Project-3
A high similarity in 16s and 23s rRNA comparisons of M. pneumoniae and C. M. luminyensis, C. M. intestinalis and C. M. alvus suggest these two groups had a common evolutionary ancestor that lacks cell walls and dwelled in the human body.

You will need a few files in order to adequately run the code:
1) Jupyter notebook
2) FASTA files of sequences used (uploaded here)

Information about where the FASTA files were found:
  Three M. pneumoniae 16s rRNA and one 16s rRNA per archaea species are provided for the first local pairwise alignment comparison. Three M. pneumoniae 23 rRNA and one 23 rRNA per archaea species are provided for the second local pairwise alignment comparison. All 16s / 23s rRNA gene sequences are from GenBank, the NIH genetic sequence database. GenBank is part of “International Nucleotide Sequence Database Collaboration” with the DataBank of Japan and European Nucleotide Archive. As of February 2021, there are 226 million sequences in GenBank alone, and 1.5 billion sequences in Whole Genome Sequencing (WGS) division. Genes of interest can be searched by keywords at GenBank website (https://www.ncbi.nlm.nih.gov/genbank/). 
  Genbank provided for three partial 16s rRNA gene sequence, and one 23s rRNA gene sequence of M. pneumoniae, as well as one 16s rRNA and one 23s rRNA sequences for each archaea species. M. pneumoniae sequences were found by manually searching the keywords “Mycoplasma pneumoniae” with corresponding rRNA gene (16s/23s) and selecting to download sequences as FASTA files. Archaea 16s / 23s sequences were found by searching the whole genome and selectively looking for 16s regions, and downloading the selected region via “selected region” function on GenBank search. These FASTA files were loaded as strings using SeqIO package from Biopython.
