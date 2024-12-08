# pt-dec
[![Build Status](https://travis-ci.org/vlukiyanov/pt-dec.svg?branch=master)](https://travis-ci.org/vlukiyanov/pt-dec) [![codecov](https://codecov.io/gh/vlukiyanov/pt-dec/branch/master/graph/badge.svg)](https://codecov.io/gh/vlukiyanov/pt-dec)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/5877a6b3baa342c3bb2d8f4a4c94f8dd)](https://app.codacy.com/app/vlukiyanov/pt-dec?utm_source=github.com&utm_medium=referral&utm_content=vlukiyanov/pt-dec&utm_campaign=Badge_Grade_Settings)

PyTorch implementation of a version of the Deep Embedded Clustering (DEC) algorithm. Compatible with PyTorch 1.0.0 and Python 3.6 or 3.7 with or without CUDA.

This follows (*or attempts to; note this implementation is unofficial*) the algorithm described in "Unsupervised Deep Embedding for Clustering Analysis" of Junyuan Xie, Ross Girshick, Ali Farhadi (<https://arxiv.org/abs/1511.06335>).

## Examples

An example using MNIST data can be found in the `examples/mnist/mnist.py` which achieves around 85% accuracy.

Here is an example [confusion matrix](http://scikit-learn.org/stable/modules/generated/sklearn.metrics.confusion_matrix.html), true labels on y-axis and predicted labels on the x-axis.

![Alt text](confusion.png)

