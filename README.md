# Human Gut Microbiome Analysis
Code for __"Absence of enterotypes in the human gut microbiomes reanalyzed with non-linear dimensionality reduction method"__ paper.
It is advised to run notebooks in the order mentioned below:

1. Preprocessing.ipynb
2. Intrinsic_dim_estimation.ipynb
3. Manifold_learning.ipynb
4. Autoencoders.ipynb
5. Clustering.ipynb

Synthetic_data.ipynb - generates simple synthetic datasets. Re-run the whole pipeline (1-4) for synthetic datasets results.
Clustering-synth.ipynb - generates clustering results (5) for synthetic datasets.
Clustering-small.ipynb - generates clustering results for original datasets, see Supporting information Text S3 for details.
Clustering-ent.ipynb - generates clustering metrics based on pre-defined artificial partition into enterotypes, see Supporting information Text S4 for details.
Visualization_separate.ipynb - visualizes continuous specificity of the data points distribution.
Visualization_merged.ipynb - demonstrates batch effect for merged AGP and HMP datasets.

The data is available on figshare by DOI: 10.6084/m9.figshare.19091423
