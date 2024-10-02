# Alignment

Accurately aligning spatial transcriptomics slices and therefore reconstructing 3D structures forms the backbone for subsequent 3D and even 4D analyses. Spateo develops a mathematical models that able to do nonrigid and partial alignment. With the help of GPU acceleration, Stochastic Variational Inference (SVI), inducing variables, and sparse computation, Spateo achieves very high efficiency and scalability. Here, we first demonstrate how Spateo performs basic slices alignment, and how to utilize non-rigid and partial alignment in Spateo.

```{toctree}
:maxdepth: 0
:titlesonly: true

./3_alignment/1. Basic usage of Spateo alignment for 2D slices.ipynb
./3_alignment/2. Nonrigid alignment of Spateo for 2D slices.ipynb
./3_alignment/3. Partial alignment of Spateo for 2D slices.ipynb
./3_alignment/4. Using GPU SVI Sparse calculation for efficiency and scalibity.ipynb

```

With pairwise alignment by chain rule, Spateo is able to reconstruct entire 3D tissues based on consecutive slices. Considering the accumulation of errors in the chain rule, global refinement is further introduced, which generalizes the Spateo pairwise and models multiple slices instead. We include two examples on:

```{toctree}
:maxdepth: 0
:titlesonly: true

./3_alignment/5. 3D reconstruction with pairwise alignment.ipynb
./3_alignment/6. Global refinement by considering multiple slices.ipynb

```


Spateo's pairwise-global alignment scheme is able to reconstruct a 3D embryo that is coherent and smooth in terms of geometry and gene expression across the 3D space. However, it should be noted that the reconstructed result is sometimes slightly incompatible with the actual structure, which is also the so-called "Banana problem". In Spateo, we design an algorithm to accurately recover the true anatomy structure by incorporating additional shape geometry information without destroying the full embryo, which is shown in the below notebook:

```{toctree}
:maxdepth: 0
:titlesonly: true

./3_alignment/7. Incorporating mesh information to improve 3D reconstruction.ipynb

```

