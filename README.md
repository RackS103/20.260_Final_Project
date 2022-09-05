# 20.260 Final Project
Rachit Mukkamala - May 8, 2022

## Project Summary

In this project, I report an analysis of SCC proteomics data from the paper *["Proteogenomic Landscape of Squamous Cell Lung Cancer"](https://doi.org/10.1038/s41467-019-11452-x)* by Stewart et al. (2019) using both unsupervised and supervised machine learning algorithms. My unsupervised analysis showed that SCC tumors can be separated into two distinct
subtypes, one of which is characterized by high expression of mRNA processing proteins/low expression
of secretory proteins, and the other which has the exact opposite signature.


My supervised analysis revealed that it is indeed possible to identify associations between tumor protein
abundances and macroscopic clinical/histological outcomes. The key to my approach was that it used
supervised PLS modeling to combine small changes in individual protein abundances into larger latent
variables, which were then easily able to separate out samples by their clinical features. The most interesting
findings from my supervised modeling were that: (1) B-cell infiltration is associated with increased
ribosomal pathway expression, (2) higher tumor stage/severity is associated with increased
mitochondrial/cell respiration protein expression, and (3) tumor recurrence is associated with increased
abundance of DNA replication proteins and decreased abundance of lysosomal proteins. Apart from these
large-scale trends, my analysis yielded rank-ordered lists of key proteins involved in seven key clinical
variables which provides a very convenient starting point for researchers looking to validate new targets
for SCC therapies
