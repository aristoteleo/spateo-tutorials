# Cell-cell interaction

Spateo features numerous methods for investigating cell-cell communication from single-cell spatial transcriptomics, 
including

1) Ligand-receptor interaction prediction (by computation of the product) conditioned on spatial proximity (and 
   ligand-receptor enrichment analysis, in the same vein as differential expression to compute spatial 
   region-specific enrichment).

```{toctree}
:maxdepth: 0
:titlesonly: true

./6_cci/1_cell-cell_communication_inference.ipynb
```

2) Estimation of the impact of ligand/receptor signaling on expression of genes of interest 
   via spatially-weighted generalized linear modeling.

```{toctree}
:maxdepth: 0
:titlesonly: true

./6_cci/2_cell-cell_interaction_effects_modeling.ipynb
```

Other tutorials coming soon!

These tools are applied in the Spateo manuscript in the context of the embryonic mouse brain. To reproduce the
figures in this manuscript, follow the following tutorials, starting with main figure 6 and supplementary 
figure 6:

```{toctree}
:maxdepth: 0
:titlesonly: true

./6_cci/Spateo_figure_6.ipynb
```

Supplementary figure 6 to come soon...

Supplementary figure 5 also includes a few additional contexts/spatial datasets. To reproduce these figures, 
follow the following tutorial:

```{toctree}
:maxdepth: 0
:titlesonly: true

./6_cci/Spateo_figure_S5.ipynb
```
