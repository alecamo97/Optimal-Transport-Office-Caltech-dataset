# Optimal-Transport-Office-Caltech-dataset

The objective of this project is to implement two different domain adaptation methods and to test them on the real-world computer vision ***Office/Caltech data set.*** The two methods are: ***subspace alignment*** and ***Entropic regularized optimal transport.***

`subspace alignment:` aims to project the labeled source and unlabeled target samples $S$ and $T$ in two subspaces spanned by their principal components so that the divergence between the two domains is minimized.

`Entropic regularized optimal transport:` It uses the *Sinkhorn-Knopp algorithm* to solve the entropic regularized OT problem between two empirical distributions of data matrices $S$ and $T$. This algorithm iteratively balances row and column sums in the transport matrix.
