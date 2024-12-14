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

The code included analysis for:
```Fig. 1a```: Venn diagram showing the pangenome of _Lm_.
```Supplementary Fig. 1a```: Comparing observed and predicted pangenome size of _Lm_ lineages.
```Fig. 1b```: Functional enrichment analysis of COG categories for lineage-associated genes.
```Fig. 1c```: Comparison of genome size among _Lm_ lineages.
```Fig. 1d```: Comparison of GC content among _Lm_ lineages.
```Fig. 1e```: Comparison of Listeria pathogenicity island (LIPI) genes among _Lm_ lineages.
```Fig. 1f```: Comparison of internalin (_inl_) genes among _Lm_ lineages.
```Fig. 1g```: Comparison of stress survival islet (SSI) genes among _Lm_ lineages.
```Supplementary Fig. 1b```: Comparison of antibiotic resistance gene (ARG) among _Lm_ lineages.
```Fig. 1h```: Comparison of insetion sequence (IS) among _Lm_ lineages.
```Fig. 1i```: Comparison of transposons among _Lm_ lineages.
```Supplementary Fig. 1c```: Comparison of prophage sequence among _Lm_ lineages.
< br / > 
```Fig. 2a```: Venn diagram showing the pangenome of _Lm_.





