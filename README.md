# NeurlPS18
NeurlPS18's paper: Understanding Regularized Spectral Clustering via Graph Conductance.

by Yilin Zhang and Karl Rohe.

paper: https://arxiv.org/abs/1806.01468

video: https://youtu.be/lOCoa3hYR4Y

poster: https://github.com/yzhang672/NeurlPS18/blob/master/regCut-poster.pdf



This paper uses the relationship between graph conductance and spectral clustering to study (i) the failures of spectral clustering and (ii) the benefits of regularization. The explanation is simple. Sparse and stochastic graphs create a lot of small trees that are connected to the core of the graph by only one edge. Graph conductance is sensitive to these noisy dangling sets. Spectral clustering inherits this sensitivity. The second part of the paper starts from a previously proposed form of regularized spectral clustering and shows that it is related to the graph conductance on a regularized graph. We call the conductance on the regularized graph CoreCut. Based upon previous arguments that relate graph conductance to spectral clustering (e.g. Cheeger inequality), minimizing CoreCut relaxes to regularized spectral clustering. Simple inspection of CoreCut reveals why it is less sensitive to small cuts in the graph. Together, these results show that unbalanced partitions from spectral clustering can be understood as overfitting to noise in the periphery of a sparse and stochastic graph. Regularization fixes this overfitting. In addition to this statistical benefit, these results also demonstrate how regularization can improve the computational speed of spectral clustering. We provide simulations and data examples to illustrate these results.
