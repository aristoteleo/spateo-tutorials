# Cell-cell interaction

Spateo features numerous methods for investigating cell-cell communication from single-cell spatial transcriptomics, 
including

1) Ligand-receptor interaction prediction (by computation of the product) conditioned on spatial proximity (and 
   ligand-receptor enrichment analysis, in the same vein as differential expression to compute spatial 
   region-specific enrichment). This provides an indication of the most prominent pairs of ligands & receptors
   expressed by cell type pairs, which may be involved in signaling between cells of the given types. For this
   tutorial, we demonstrate on a 2D example, using a slice collected from the injured telencephalon of an axolotl. 

```{toctree}
:maxdepth: 0
:titlesonly: true

./6_cci/1_cell-cell_communication_LR_coexpression_analysis.ipynb
```

2) Estimation of the impact of ligand/receptor signaling on expression of genes of interest 
   via spatially-weighted generalized linear modeling. Spateo integrates ligand-receptor interaction predictions
   with robustly built biological knowledge networks to best infer how ligand-receptor interaction may result in 
   upregulation of particular genes. For this tutorial, we demonstrate on a 3D example; specifically, a portion of
   the developing diencephalon (in the brain) of a mouse embryo at the E11.5 stage. It is broken into two parts:
   downloading the data and selecting target genes for the model, running the model and performing selected downstream
   analyses. 

```{toctree}
:maxdepth: 0
:titlesonly: true

./6_cci/2_cell-cell_interaction_effects_modeling_selecting_target_genes.ipynb
./6_cci/2_cell-cell_interaction_effects_modeling_inference.ipynb
```
