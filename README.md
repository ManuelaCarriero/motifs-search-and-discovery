# motifs-search-and-discovery
## Summary
This project provides an introspection into what are motifs in molecular biology and their biological importance together with methods to detect DNA
and protein sequence motifs. The application of this work is focused on the
hyperthermophilic archaeon Pyrococcus Furiosus and a genetically tractable
Pyrococcus Furiosus strain called COM1 that has the particular characteristics to resist to gamma irradiation despite that a number of DNA repair
proteins are actually or potentially disrupted.
The known diversity of metabolic strategies and physiological adaptations of
archaeal species to extreme environments is extraordinary and in this project,
some possible mechanisms of metabolic adaptation of COM1 are studied
by searching for overrepresented DNA sequence motifs related to radioresistance. The results show that the DNA sequence motif GARGADRHTGHGGMAGAGDTY, which is detected by the software MEME using a set of 8
Ferritin-like DNA sequence genes involved in the protection against oxidative damage, is overrepresented in COM1 with respect to the reference P.
Furiosus genome. This can suggest that the radioresistance of COM1 is due
to amplification of genes encoding proteins which belong to Ferritin family,
or of genes with similar functions, following the destruction or inactivation
of DNA repair genes.

## Software
Mainly [The MEME Suite 5.5.1](https://meme-suite.org/meme/doc/overview.html?man_type=web) plus Python 3.9 (the code is in pdf file [Motifs_ManuelaCarriero.pdf](https://github.com/ManuelaCarriero/motifs-search-and-discovery/blob/main/Motifs_ManuelaCarriero.pdf).

## Data
* Pyrococcus furiosus COM1, complete genome https://www.ncbi.nlm.nih.gov/nuccore/CP003685
* Pyrococcus furiosus DSM 3638, complete sequence https://www.ncbi.nlm.nih.gov/nuccore/NC_003413.1