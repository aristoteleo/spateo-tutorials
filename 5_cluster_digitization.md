# Clustering and digitization

Spateo recommands using a combination strategy of spatial domain clustering on binning data and single-cell clustering on spatially segmented cells, to leverage high-resolution spatial transcriptomics data to reveal both anatomical and cellular heterogeneity. Here we  demonstrate how spateo obtains spatial domains with our new spatially constrained clustering (SCC) algorithm, and how to harmonize and visualize spatial domain and cell type characterization.

```{toctree}
:maxdepth: 0
:titlesonly: true

./2_cluster_digitization/1_bin_scc.ipynb
./2_cluster_digitization/2_cellbin_visualize.ipynb
```



Combining anatomical and cellular information enables multiple aspects to perform spatial statistical analysis. We include two simple showcases on:

1. summarizing cell type composition in each domain, or domain specificity of cell types.
2. cell type co-localization analysis.

```{toctree}
:maxdepth: 0
:titlesonly: true

./5_cluster_digitization/3_combined_analysis.ipynb
```



Spateo employs Moran's I to search spatially informative genes with interesting expression patterns. Genes with similar patterns are then grouped into archetypes, enabling functional annotation on those patterned region.

```{toctree}
:maxdepth: 0
:titlesonly: true

./5_cluster_digitization/4_svg_archetype.ipynb
```



Digitization aims to quantify and meature the spatial pattern or variation of biological features (i.e. gene expression, cell type, etc.). Spateo implemented two basic digitizing operation to tackle most biological scenarios. 

```{toctree}
:maxdepth: 0
:titlesonly: true

./5_cluster_digitization/5_borderline_digitization.ipynb
./5_cluster_digitization/6_layer_column_digitization.ipynb
```

