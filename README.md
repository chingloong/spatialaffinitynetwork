# Spatial Affinity Networks
PyTorch Implementation of the paper Learning Affinity via Spatial Propagation Networks

[Work in Progress]

FCN-8 Code and Model adopted from https://github.com/wkentaro/pytorch-fcn

The paper propose to learn a spatial affinity matrix by consturcting a row-wise / column-wise linear propagation model where each pixel in the current row/column incorporates the information from its three adjacent pixels in the previous row/column. The idea is to train a CNN that generates the weights of a recursive filter conditioned on an input image. 


