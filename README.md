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

- 
- scikit-bio
- statsmodel
- rpy2
- 
- 
- colorcet
- geopy
- mpu
- biopython
- haversine
- python-Levenshtein

## Required R packages
- vegan

> [!NOTE]
> For running the R code in the Jupyter notebook install ```rpy2``` package using ```pip install rpy2```
> - Use the command ```%load_ext rpy2.ipython``` for using this library before executing the R code in the python notebook
> - Ensure your R and Python environments are correctly configured and that ```rpy2``` can access R.
> - For any R code execution directly in the notebook, make sure to include the appropriate ```%R``` or ```%%R``` syntax when working with the ```rpy2``` extension.


## Structure
```Lm_pangenome_MS.ipynb```: code used for analysis and generate plots in Figs. 1a-f, 2f, 3c-d, 4a-d,f-g and Supplementary Figs. 1, 4, 6, 7.

This code include analysis for:
```Fig. 1a```: Venn diagram showing the pangenome of _Lm_
```Fig. 1b```: Functional enrichment analysis of COG categories for lineage-associated genes
```Fig. 1c```:
```Fig. 1d```:
```Fig. 1e```:




