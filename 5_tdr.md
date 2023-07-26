# Three dimensional reconstruction

Spateo is equipped with sophisticated methods for building 3D spatiotemporal models by aligning serial sections of
tissue, organ or embryos across different stages that can be measured by stereo-seq or other high definition spatial
transcriptomics technologies. The ability of Spateo to 3D spatiotemporal models enables us to evolve from reductionism
of single cells to the holisticism of tissues and organs, heralding a paradigm shift in moving toward studying the
ecology of tissue and organ while still offering us the opportunity to reveal associated molecular mechanisms.

Here we will present a series of notebooks that showcase:

1. how we can leverage Spateo to build whole body 3D point-cloud, surface and volume models of drosophila embryo and its tissues.
2. how we can leverage Spateo to build AP or DV axis of drosophila embryo and backbone of drosophila tissues.
3. how we can leverage Spateo to perform novel morphometric analyses.
4. how we can leverage Spateo to learn continuous expression pattern in the 3D volume model by various novel methods (Gaussian Process, SparseVFC, Deep Learning, etc.).
5. how we can leverage Spateo to generate gorgeous animations of 3D models.

```{toctree}
:maxdepth: 0
:titlesonly: true

./5_tdr/3D Reconstruction.ipynb
./5_tdr/Axis&Backbone.ipynb
./5_tdr/Morpholoy.ipynb
./5_tdr/Interpolations.ipynb
./5_tdr/Animation.ipynb
```