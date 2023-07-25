# Three dimensional reconstruction

Spateo is equipped with sophisticated methods for building 3D spatiotemporal models by aligning serial sections of
tissue, organ or embryos across different stages that can be measured by stereo-seq or other high definition spatial
transcriptomics technologies. The ability of Spateo to 3D spatiotemporal models enables us to evolve from reductionism
of single cells to the holisticism of tissues and organs, heralding a paradigm shift in moving toward studying the
ecology of tissue and organ while still offering us the opportunity to reveal associated molecular mechanisms.

Here we will present a series of notebooks that showcase:

1. how we can leverage Spateo to build whole body 3D point-cloud, surface and volume models of drosophila embryo at the E8-10 stage.
2. how we can leverage Spateo to build 3D surface and volume models of each tissue type.
3. how we can leverage Spateo to perform novel morphometric analyses.
4. how we can leverage Spateo to learn continuous expression pattern in the 3D volume model by kernel methods.
5. how we can leverage Spateo to learn continuous expression pattern in the 3D volume model by a new deep learning methods.

```{toctree}
:maxdepth: 0
:titlesonly: true

./5_3d_reconstruction/3D Reconstruction.ipynb
./5_3d_reconstruction/2_3d_models_reconstruction.ipynb
./5_3d_reconstruction/3_subpopulations_reconstruction.ipynb
./5_3d_reconstruction/4_morpholoy.ipynb
./5_3d_reconstruction/5_ap&dv_diff_analysis.ipynb
./5_3d_reconstruction/6_backbone_diff_analysis.ipynb
./5_3d_reconstruction/visualization_single_model.ipynb
./5_3d_reconstruction/animation_3d_model.ipynb
```