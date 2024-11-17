# Optimal-Transport-Office-Caltech-dataset

The objective of this project is to implement two different domain adaptation methods and to test them on the real-world computer vision ***Office/Caltech data set.*** The two methods are: ***subspace alignment*** and ***Entropic regularized optimal transport.***

`subspace alignment:` aims to project the labeled source and unlabeled target samples $S$ and $T$ in two subspaces spanned by their principal components so that the divergence between the two domains is minimized.

`Entropic regularized optimal transport:` It uses the *Sinkhorn-Knopp algorithm* to solve the entropic regularized OT problem between two empirical distributions of data matrices $S$ and $T$. This algorithm iteratively balances row and column sums in the transport matrix.

### **Dataset**

The Office-Caltech dataset is widely used in domain adaptation research and includes images from four distinct domains: Amazon (online product images), DSLR, Webcam,
and Caltech. This setup simulates real-world applications where data from different sources exhibit significant variability.

For this project, two numerical datasets that repsent the images were used

- **SURF:** extracts image features using Speeded Up Robust Features (SURF), a technique known for capturing local keypoints and creating feature vectors based on their spatial distribution.
- **CaffeNet4096:** it's a representation of a pre-trained CaffeNet model, which is a dense, high-dimensional (4096-dimensional) feature space based on hierarchical representations of the image content.
