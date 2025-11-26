# Lm_pangenome_MS
Code used to replicate data analyses in the manuscruipt "Disentangling the impacts of abiotic and biotic environmental factors and dispersal dynamics on the pangenome plasticity of bacterial pathogens in soil."

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
```Lm_pangenome_MS.ipynb```: The code used for analysis and to generate the plots in Figs. 1a–d, 1g, 2a–d, 2g, 3a-h, 4a, and Supplementary Figs. 1-2, 4, 6-11, and 14.

The code included analysis for:\
```Supplementary Fig. 1```: Pangenome size and gene richness of _L. monocytogenes_ (_Lm_).

```Fig. 1a```: Variation partitioning analysis (VPA) showing the variation of gene richness explained by geolocation, soil properties, climate, and surrounding land use.\
```Fig. 1b```: Variation of gene richness for Clusters of Orthologous Genes (COGs) explained by abiotic factors in VPA.\
```Fig. 1c```: Spearman’s correlation between abiotic factors and gene richness, overall and for significant COGs identified in VPA.\
```Supplementary Fig. 2```: Frequency of abiotic environmental factors significantly correlated with gene richness for COGs, sorted in descending order.\
```Fig. 1d```: Redundancy Analysis (RDA) biplot illustrating the relationships between the _Lm_ accessory genome and 31 abiotic variables selected by Lasso regularization.\
```Fig. 1g```: Enrichment of COGs among abiotic-linked genes.

```Fig. 2a```: VPA showing the variation of gene richness explained by abiotic and biotic factors.\
```Fig. 2b```: Variation of gene richness for COGs explained by abiotic and biotic factors in VPA.\
```Fig. 2c```: Spearman’s correlation between the relative abundance of bacterial phyla and gene richness, overall and for significant COGs identified in VPA.\
```Supplementary Fig. 4```: Frequency of biotic factors significantly correlated with gene richness for COGs, sorted in descending order.\
```Fig. 2d```: RDA biplot illustrating the relationships between the _Lm_ accessory genome and 17 phyla selected by Lasso regularization.\
```Supplementary Fig. 6```: Functions of abiotic- and biotic-linked genes.\
```Fig. 2g```: Enrichment of COGs among exclusive biotic-linked genes.

```Fig. 3a```: Map showing the distribution of _Lm_ lineages in soils across the US.\
```Supplementary Fig. 7```: Abiotic factors compared among _Lm_ lineages.\
```Fig. 3b```: Multidimensional scaling (MDS) analysis for _Lm_ lineages based on abiotic conditions.\
```Supplementary Fig. 8```: Relative abundance of bacterial phyla compared among _Lm_ lineages.\
```Fig. 3c```: MDS analysis for _Lm_ lineages based on bacterial community composition using weighted UniFrac distances based on OTUs.\
```Fig. 3d```: Pangenome sizes of _Lm_ lineages, stratified into core and accessory genome sizes, and predicted pangenome sizes based on 100 genomes per lineage.\
```Fig. 3e```: Enrichment of COGs among lineage-associated genes.\
```Fig. 3f```: Genome size and GC content compared among _Lm_ lineages.\
```Supplementary Fig. 9```: Genetic elements compared among _Lm_ lineages.\
```Fig. 3g```: VPA showing the variation of gene richness for lineage III explained by abiotic and biotic factors.\
```Fig. 3h```: Variation of gene richness for COGs explained by abiotic and biotic factors at the species level and within lineage III.

```Fig. 4a```: Linear regression for genetic similarities measured by average nucleotide identity (ANI) and geographic distances for _Lm_ lineage I, II, and III.\
```Supplementary Fig. 10```: Dispersal patterns of _Lm_ lineages after downsampling.\
```Supplementary Fig. 11```: Dispersal patterns of _Lm_ lineage II after excluding the distant cluster.

```Supplementary Fig. 14```: Genomic features compared between epidemiologically linked soil and clinical _Lm_ lineage I isolates.
