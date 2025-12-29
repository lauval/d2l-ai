# Dive Into Deep Learning - Notes

## Overview

So the composition of a deep learning model is essentially:

- a dataset
- a model whose goal it is to uncover some obscure relationship between the variables (aka features or inputs) and the predictand (aka label in the case of supervised learning)
- an objective function (aka loss function when we flip the sign so that smaller values are better) to measure the loss incurred at each training step (think RMSE for example)
- an optimisation algorithm (think gradient descent) to nudge the model towards a smaller loss function for each feature at each training step in the learning loop

The goal is to essentially program a system using data.

A performant system:

- generalises well i.e. doesn't overfit on the training data
-
