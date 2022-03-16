# Unsupervised-learning
we explore neural network models for solving unsupervised problems.
We focus on autoencoders, the aim is to learn a representation for a set of data, reduc-
ing the dimensionality and then try to regenerate as close as possible the original input.
I decide to implement a convolutional autoencoder and optimize hyperparameters throught
optuna random-search and a Kfold cross-validation. For time computa-
tion reason, I use the founded hyperparameters also in the denoising and in the variational autoencoder
but the search could be done in the same way.
