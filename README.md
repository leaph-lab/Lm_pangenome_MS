# Lm_pangenome_MS
Code used to replicate data analyses in the manuscruipt "Pangenome fluidity of _Listeria monocytogenes_ is shaped by environmental pressures from climate, soil properties, and bacterial communities and dispersal dynamics."

## Required Python packages
- pandas
- numpy
- matplotlib
- seaborn
- scipy
- statsmodels
- scikit-learn
- shapely
- statannot
- matplotlib_venn
- scikit-bio
- shapefile
- rpy2

## Required R packages
- vegan
- tidyverse

> [!NOTE]
> For running the R code in the Jupyter notebook install ```rpy2``` package using ```pip install rpy2```
> - Use the command ```%load_ext rpy2.ipython``` for using this library before executing the R code in the python notebook
> - Ensure your R and Python environments are correctly configured and that ```rpy2``` can access R.
> - For any R code execution directly in the notebook, make sure to include the appropriate ```%R``` or ```%%R``` syntax when working with the ```rpy2``` extension.

## Structure
```Lm_pangenome_MS.ipynb```: The code used for analysis and to generate the plots in Figs. 1a–d, 1f, 2a–d, 2f-i, 3a-h, and Supplementary Figs. 1, 2, 4, 6-8, and 11.

The code included analysis for:\
```Supplementary Fig. 1```: Pangenome size and gene richness of _Lm_.

```Fig. 1a```: Variation partitioning analysis (VPA) and permutation tests to explain overall gene richness using abiotic variables.\
```Fig. 1b```: VPA and permutation tests to explain gene richness, stratified by Clusters of Orthologous Groups (COGs), using abiotic variables.\
```Fig. 1c```: Spearman's correlation between gene richness and abiotic variables.\
```Supplementary Fig. 2```: Proportion of abiotic variables associated with gene richness across COGs in _Lm_.\
```Fig. 1d```: Redundancy Analysis (RDA) between the accessory genome of _Lm_ and abiotic variables.\
```Fig. 1f```: Enrichment of COG functions among abiotic-linked genes.

```Fig. 2a```: VPA and permutation tests to explain overall gene richness using both abiotic and biotic (relative abundance of bacterial phyla) variables.\
```Fig. 2b```: VPA and permutation tests to explain gene richness, stratified by COGs, using both abiotic and biotic variables.\
```Fig. 2c```: Spearman's correlation between gene richness and biotic variables.\
```Supplementary Fig. 4```: Proportion of bacterial phyla associated with gene richness across COGs in _Lm_.\
```Fig. 2d```: RDA between the accessory genome of _Lm_ and biotic variables.\
```Fig. 2f```: Enrichment of COG functions among biotic-linked genes.\
```Fig. 2g```: Venn diagram of overlap between abiotic- and biotic-linked genes.\
```Fig. 2h```: Enrichment of COG functions among uniquely abiotic-linked genes.\
```Fig. 2i```: Enrichment of COG functions among uniquely biotic-linked genes.

```Fig. 3a```: Distribution of _Lm_ lineages in the soil accross the US.\
```Supplementary Fig. 6```: Mann-Whitney _U_ test to identify abiotic variables significantly differing among _Lm_ lineages.\
```Fig. 3b```: Multidimensional scaling (MDS) on abiotic variables among _Lm_ lineages.\
```Supplementary Fig. 7```: Mann-Whitney _U_ test to identify bacterial phyla with significantly different relative abundance among _Lm_ lineages.\
```Fig. 3c```: MDS of bacterial community compositions using weighted UniFrac distances of OTUs among _Lm_ lineages.\
```Fig. 3d```: Pangenome composition across _Lm_ lineages, stratified into core and accessory genes, and predicted pangenome sizes for _Lm_ genomes based on 100 genomes per lineage.\
```Fig. 3e```: Functional enrichment analysis of COGs for lineage-associated genes.\
```Fig. 3f```: Comparison of genome size and GC content among _Lm_ lineages.\
```Supplementary Fig. 8```: Comparison of _Listeria_ pathogenicity island (LIPI) genes, internalin (inl) genes, stress survival islet (SSI) genes, antibiotic resistance genes (ARGs), and mobile genetic elements (MGEs), including proportions of insertion sequences (IS), transposons, and prophages, among _Lm_ lineages.\
```Fig. 3g```: VPA and permutation tests to explain overall gene richness using both abiotic and biotic variables for _Lm_ lineage III.\
```Fig. 3h```: Comparison of the variation in gene richness explained by abiotic and biotic variables across COGs between species level and Lm lineage III.

```Supplementary Fig. 11```: Comparison of genome size, GC content, LIPI-1, LIPI-2, LIPI-4, _inl_, ARG, IS, transposons, and prophage between soil and clinical isolates.
