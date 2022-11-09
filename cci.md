# Cell-cell interaction

Spateo models cell-cell communication and spatial niches via a general spatial lag regression approach to detect significant ligand-receptor interactions based on a spatial transcriptomic dataset with single cell resolution(Stereo-seq). Spateo implements cell-cell interaction prediction based on ligand-receptor products conditioned on spatial proximity. Meanwhile,Spateo is able to estimate the impact of niche factors and cell type-specific ligand-receptor interactions on expression of molecules of interest with spatially-aware generalized linear modeling that enables selection of multiple non-normal distribution assumptions. Spateo also integrates ligand-specific enrichment analysis, Similar to the differential gene analysis, We can observe that the ligand receptor pair specifically enriched in a certain spatial region. In addition, Spateo also provides an interactive lasso of regions of interest based on clustering results. 




```{toctree}
:maxdepth: 0
:titlesonly: true

./3_cci/1_cell-cell_communication_inference.ipynb
./3_cci/2_microenvironment_modeling_analysis.ipynb
./3_cci/3_ligand_receptor_specfic_enrichment_analysis.ipynb
./3_cci/4_interactive_lasso_of_regions_of_interest.ipynb
```
