# Lm_pangenome_MS
Code used to replicate data analyses in the manuscruipt "The pangenome evolution of _Listeria monocytogenes_ is associated with both abiotic factors and bacterial community composition"

## Required Python packages
- pandas
- numpy
- statsmodels
- matplotlib
- seaborn
- scipy
- itertools
- collections
- statannot
- matplotlib_venn
- basemap
- pyshp 
- shapely
- scikit-learn
- scikit-bio
- statsmodel
- rpy2

## Required R packages
- vegan

> [!NOTE]
> For running the R code in the Jupyter notebook install ```rpy2``` package using ```pip install rpy2```
> - Use the command ```%load_ext rpy2.ipython``` for using this library before executing the R code in the python notebook
> - Ensure your R and Python environments are correctly configured and that ```rpy2``` can access R.
> - For any R code execution directly in the notebook, make sure to include the appropriate ```%R``` or ```%%R``` syntax when working with the ```rpy2``` extension.

## Structure
```Lm_pangenome_MS.ipynb```: The code used for analysis and to generate the plots in Figs. 1a–i, 2a–b, 2d–f, 3a, 3c–f, 4d, and Supplementary Figs. 1–9 and 12.

The code included analysis for:\
```Fig. 1a```: Venn diagram showing the pangenome of _Lm_.\
```Supplementary Fig. 1a```: Comparing observed and predicted pangenome size of _Lm_ lineages.\
```Fig. 1b```: Functional enrichment analysis of COG categories for lineage-associated genes.\
```Fig. 1c```: Comparison of genome size among _Lm_ lineages.\
```Fig. 1d```: Comparison of GC content among _Lm_ lineages.\
```Fig. 1e```: Comparison of Listeria pathogenicity island (LIPI) genes among _Lm_ lineages.\
```Fig. 1f```: Comparison of internalin (_inl_) genes among _Lm_ lineages.\
```Fig. 1g```: Comparison of stress survival islet (SSI) genes among _Lm_ lineages.\
```Supplementary Fig. 1b```: Comparison of antibiotic resistance gene (ARG) among _Lm_ lineages.\
```Fig. 1h```: Comparison of insetion sequence (IS) among _Lm_ lineages.\
```Fig. 1i```: Comparison of transposons among _Lm_ lineages.\
```Supplementary Fig. 1c```: Comparison of prophage sequence among _Lm_ lineages.

```Supplementary Fig. 2```: Abiotic factors significantly different among _Lm_ lineages.

```Supplementary Fig. 3```: Multidimensional scaling (MDS) on abiotic factors among _Lm_ lineages.

```Fig. 2a```: Distribution of _Lm_ lineages in the soil accross the US.\
```Fig. 2b```: Redundancy Analysis (RDA) between the accessory genome of _Lm_ and abiotic factors.\
```Fig. 2d```: Frequency of abiotic factors linked to lineage-associated genes.\
```Supplementary Fig. 4```: Prevalence of COG functional categories of abiotic-linked lineage genes.\
```Fig. 2e```: Abiotic-linked lineage genes with the lowest _P_-values (top three).\
```Fig. 2f```: Enrichment of COG functions among abiotic-linked lineage genes.

```Supplementary Fig. 5a```: Heatmap of the relative abundance of operational taxonomic units (OTUs) that are significantly different among _Lm_ lineage.\
```Supplementary Fig. 5b```: Taxonomic classification of OTUs significantly differing among _Lm_ lineages.

```Supplementary Fig. 6```: Relative abundance of bacterial phyla among _Lm_ lineages.

```Supplementary Fig. 7```: Relative abundance of taxa at other taxonomic ranks.\
```Supplementary Fig. 7a```: Relative abundance of class among _Lm_ lineages.\
```Supplementary Fig. 7b```: Relative abundance of order among _Lm_ lineages.\
```Supplementary Fig. 7c```: Relative abundance of family among _Lm_ lineages.\
```Supplementary Fig. 7d```: Relative abundance of genus among _Lm_ lineages.

```Supplementary Fig. 8```: MDS of OTUs among _Lm_ lineages.\
```Supplementary Fig. 8a```: Weighted UniFrac distance.\
```Supplementary Fig. 8b```: Bray-Curtis distance.

```Fig. 3a```: RDA between the accessory genome of _Lm_ and surrounding bacterial communities.\
```Fig. 3c```: Taxonomic classification of OTUs included in RDA.\
```Fig. 3d```: Frequency of OTUs linked to lineage-associated genes.\
```Supplementary Fig. 9a```: Prevalence of COG functional categories of biotic-linked lineage genes.\
```Fig. 3e```: Biotic-linked lineage genes with the lowest _P_-values (top three).\
```Fig. 3f```: Enrichment of COG functions among biotic-linked lineage genes.\
```Fig. 3g```: Percentage of lineage-associated genes in each COG functional category, uniquely linked to abiotic environmental factors, uniquely linked to bacterial communities, and linked to both factors.\
```Fig. 3h```: Enrichment of COG functions among uniquely abiotic-linked lineage genes.\
```Supplementary Fig. 9b```: Enrichment of COG functions among uniquely biotic-linked lineage genes.

```Fig. 4d```: Comparison of genome size, GC content, LIPI-1, LIPI-2, and IS between soil and clinical isolates.\
```Supplementary Fig. 12```: Comparison of LIPI-4, _inl_, ARG, transposons, and prophage between soil and clinical isolates.


