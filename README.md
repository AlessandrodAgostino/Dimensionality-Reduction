The Method 
==========

Being able to detect features that contains the majority of information
in a dataset is an essential task for prediction. It will be shown that
the method allows dimensionality reduction without the need of
projection on latent variables based techniques. The features are not
transformed allowing a direct *a posteriori* interpretation of the
results.

#### Prior Penalized regression

The first step in this pipeline is the extraction and the
*regularization* of the numerical features. Three different methods were
used for the regularization purpose:

-   Standard: Standardizing the features by removing the mean and
    scaling to unit variance.

-   MinMax: Transforming the features by scaling each feature in the
    range $[0,1]$.

-   Robust: Standardizing the features to unite variance giving less
    importance to the outliers, so in a more *robust* way.
