# Convolutional_Autoencoder_Exercise-
Using Transpose Convolution Layers for up-sampling.
Transposed convolution does not use a predefined interpolation method. It has learnable parameters.
However, the transposed convolution is the cause of the checkerboard artifacts in generated images. 
We recommends an up-sampling operation (i.e., an interpolation method) followed by a convolution operation to reduce such issues.
