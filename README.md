# Autoencoders-dimensionality-reduction
Autoencodrs and its application of dimensionality reduction
_________________________________________________________________________________________________________________________________________________________________

**Problem Statemnet**: To Understand the concept of autoencodrs and its application of dimensionality reduction for a physical probelm.

We will use the variable modulus of elasticity to check the autoencoder model (that output is same as the input) and further we will check the whether the dimension of the input dataset it reduced or not.

The equation used for the modulus of elaticity is: 

**E=a0+(a1*(x^n))** 

Here, a0, a1 and n are constants that are generated randomly in the code.

__________________________________________________________________________________________________________________________________________________________________

**Understanding autoencoders:**

Autoencoders are a type of neural network leveraged for unsupervised learning purposes that try to optimize a set of parameters to compress the input data into the latent space, spot patterns and anomalies, and improve comprehension of the behavior of the data as a whole.

An autoencoder is composed of an encoder and a decoder sub-models. The encoder compresses the input and the decoder attempts to recreate the input from the compressed version provided by the encoder. After training, the encoder model is saved and the decoder is discarded for dimensionality reduction.

**Different Use Cases of Autoencoders**

**Denoising Autoencoders**: such a model is used when we want to clean the input from some noisy patterns. It is trained by corrupting the input (using Gaussian noise, for instance) and using the original input (before noise introduction) as output.

**Generation**: a flavor of autoencoders called Variational Autoencoder (VAE) learns a probability distribution function to sample and generate new data.

**Dimensionality Reduction & Feature Selection**:Dimensionality Reduction is the process of reducing the number of dimensions by transforming the data into lower dimensions.
