Features
= Dimensions

There
should only be optimal number of features we should use in ML, after certain
limit it does not help improving the performance.

Think
about the hand written digit image dataset where we made each pixel a new
feature: for 28\*28 pixel images the digit representing pixels are always around
the center of the image, which is why using each and every pixel is not a good
idea - in fact it is increasing the computation without having any real effect
on the performance. Similarly, our model start missing the features that
actually represents the digits then we are heading for failure.

This is
why we have to find the optimal number of features.

SPARSITY
: More features with relatively small or equal amount of data point is bad
because it increases the distance between data points called 'sparsity'.

As the
distance between two points is least in 1D space, as the number of dimensions
increases the distance between the point increases even though points are
unmoved.

Performance
decreases and compute increases.

Dimensionality
Reduction : Reduces the number of columns via 1. Feature selection - Forward
selection /backward elimination or 2. Feature extraction - PCA , LDA, Tsne.
