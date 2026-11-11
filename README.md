# BoolInference

Opened 2020-06-08.

MATLAB library for inferring structure in random binary strings.

`bintraintest.m` binarizes a dataset, learns an invertible code per class with `bubblewrap`, and labels a test string by its log probability under those codes. The inference routines in `infer/` are XOR, convolution, conditional inference, and a KL-mean variant. `entropy.m` and `visualizer/` support the codes.
