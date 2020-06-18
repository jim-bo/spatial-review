# spatial-review
repository of my random walk through spatial genomics and proteomics methods.

## paper list
* [Giotto, a toolbox for integrative analysis and visualization of spatial expression data](https://www.biorxiv.org/content/10.1101/701680v2)

## Giotto: WIP
(last updated 6/18/2020)
**Summary**: 

*note 6/18/20: this is a first pass summary, will be refined as I move through the paper*

Two packages, methods and visualizations to characterize cells and identify spatial gene expression patterns in a variety of high (cellular/sub-cellular) and less-than-cellular resoltuion spatial imaging/pseudo imaging techniques. From a matrix of cell-by-gene expression and centroid/nuclear coordinates they perform cell-type assignment using established dimensionality reduction, clustering and feature ranking techniques. They have proposed several methods to identify genes which have coherent spatial expression. Finally spatial enrichment across gene profiles is determined by building a grid of nearest neighbors (deluaney or k-means+threshold) and then applying a novel HMM.


