# GSimp
GSimp is a Gibbs sampler-based missing value imputation approach.

**GSimp simulation.Rmd** is a vignette of using GSimp for the MNAR imputation and comparing GSimp with other imputation methods on simulation dataset. It also contains a simulation dataset generation algorithm.

**GSimp simulation.pdf** was knited by **GSimp simulation.Rmd**

**GSimp.R** contains the core functions for GSimp.

**MNAR_evaluation.R** contains MNAR generation and evaluation functions which are part of our missing value imputation evaluation pipeline.

**MVI_global.R** contains some basic global functions.

**Prediction_funcs.R** contains wrapper functions for different prediction models.

**real_data.csv** is a real-world targeted metabolomics dataset which contains FFAs and BAs.

**Trunc_KNN** contains kNN-TN algorithm and related functions developed by Jasmit S. Shah (https://doi.org/10.1186/s12859-017-1547-6)
