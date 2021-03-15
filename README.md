# BIMM143_Project3
Scientific Question: Will the arimoclomal drug be effective in treating ALS in humans just like it is effective in treating ALS in mice?

What is needed to run the code.
1. the jupyter notebook
2. the FASTA files for human SOD1 and HSPA1A
3. the FASTA files for mice SOD1 and HSPA1A
4. pymol is needed to part 4

Information about where FASTA file was found:
  SOD1 and HSPA1a (Hsp70) have been studied, with both their protein sequences and protein structures uploaded to databases. Protein sequences were found in the NCBI database (https://www.ncbi.nlm.nih.gov/). 
   I found the FASTA for the protein sequences of SOD1 by searching SOD1 in the NCBI database. The first two search results provided sequences for homo sapiens (https://www.ncbi.nlm.nih.gov/gene/6647) and mus musculus (https://www.ncbi.nlm.nih.gov/gene/20655). Within each page I clicked on "Download Datasets" and selected the Protein Sequences(FASTA), to download the .faa files for both. I read both of these files in jupyter by calling their directory.
   I also searched for HSPA1A – heat shock protein family A (Hsp70) member 1A, which is a shared protein in both mice (https://www.ncbi.nlm.nih.gov/gene/193740) and humans (https://www.ncbi.nlm.nih.gov/gene/3303). Within each page I clicked on "Download Datasets" and selected the Protein Sequences(FASTA), to download the .faa files for both. I read both of these files in jupyter by calling their directory.
   
   The output of this code includes protein sequence alignments and dotplots comparing mice and human sequences. It also outputs two images of SOD1 protein structure as well as a visual protein structure alignment of SOD1 protein structure between mice and humans.
