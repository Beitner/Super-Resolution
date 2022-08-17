# Super-Resolution


The purpose of this notebook is building a fully-convolutional network and using perceptual loss in order to boost the performance.

We will specifically use the task of image super-resolution to enlarge image resolution by a factor of 2.

Originally, the idea for adding perceptual loss to the regular super resolution loss was suggested in the paper "Perceptual Losses for Real-Time Style Transfer and Super-Resolution" (Johnson et al. 2016, http://svl.stanford.edu/assets/papers/JohnsonECCV16.pdf). Usually this type of task takes a long time to train, because of the complex networks used for it. In this exercise we take the ideas from this paper, but make it manageable, with a rather small network, a small number of training images and working with small images (dimensions).
