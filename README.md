# Universal_Component_Analysis
Blind source seperator for probabalistically recovering original sources from data which is not strictly non-gaussian.

Currently, I have a functioning linear solution for 2+ mixtures and 2 features.

In comparison to independent component analysis, it only uses the covariance structure of the space of possible solutions. When whitened, the covariance structure is featureless and any rotation of an orthogonal, whitened array is also orthogonal. However, the initial space of orthogonal transformations is not featureless, and it is this trick that we employ to recover the original features.
