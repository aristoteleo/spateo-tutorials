# Cell segmentation

Spateo provides existing and novel methods to obtain single-cell segmentations using either stained cells or RNA signal. When using high-resolution spatial transcriptomics assays, such as BGI's Stereo-seq, each cell is captured by many pixels (approximately 400 for Stereo-seq). This allows us to aggregate UMIs from neighboring pixels to perform single-cell segmentation, ultimately yielding a (segmented) cell x gene count matrix just like single-cell RNA-seq (scRNA-seq) assays. As a result, many of the tools and approaches developed for scRNA-seq can be applied with ease, with the added benefits of having spatial information. This tutorial will showcase the cell segmentation methods provided with Spateo.

Before we jump in, however, it is important to provide a bit of background and define terminology that will be used throughout the tutorial. The objective of cell segmentation is to obtain, for every observation in space (often called a spatial *spot*, *pixel*, or in the case of Stereo-seq a *DNA nanoball*), a label indicating if it is not a part of a cell (value of 0) or what cell it is a part of (a positive integer). Specifically, if we have an $X \times Y$ field-of-view (FOV), we want to obtain an $X \times Y$ matrix where each cell contains a non-negative integer, where each positive value indicates pixels that are occupied by a particular cell. To achieve this, we will further divide the approach into two broad steps.

1. **Segmentation**: Obtain a boolean (True/False) mask of size $X \times Y$, where True indicates pixels that are occupied by a cell, and False otherwise.

2. **Labeling**: From the boolean mask obtain previously, identify individual cells (a.k.a. *instance segmentation* in machine learning).

Note that deep learning-based methods for segmenting cell staining images often combine the two steps (i.e. the model outputs the final cell labels).

Since the approach is quite different based on whether or not a staining image is available, we provide separate tutorials for each use case.

```{toctree}
:maxdepth: 0
:titlesonly: true

./stain_segmentation.ipynb
./rna_segmentation.ipynb
```