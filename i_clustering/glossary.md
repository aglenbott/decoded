# Clustering glossary

## Summary
Clustering is an example of a non-parametric unsupervised learning algorithm.  Data is clustered into groups whose members are similar in some way.

## Proximity measures
We use proximity measures to measure similarity and dissimilarity/distance.

### Points
* Euclidean distance
* Minkowski metric (p=2 is Euclidean, p=1 is Manhattan)

### Vectors
* Cosine distance

### Sets
* Jaccard distance

## Types of clustering algorithm
There are four main types of clustering algorithm

1. ### Exclusive
Each data point must belong to a single cluster only

1. ### Overlapping
This is a fuzzy version of exclusive clustering whereby some of the data points may belong to two or more clusters.  Data points belong to each of its clusters with differing degrees of membership.

1. ### Hierarchical
Iteratively sets clusters by grouping together the two nearest clusters.  Start off with each data point belonging to its own cluster exclusively.

1. ### Probabilistic
Model-based approach using Gaussian Mixture Models.  Each cluster is assumed to be parametrised by a Gaussian distribution.  Use expectation-maximisation to determine the relevant parameters.

## References
https://towardsdatascience.com/unsupervised-learning-and-data-clustering-eeecb78b422a
https://web.stanford.edu/class/cs345a/slides/12-clustering.pdf
