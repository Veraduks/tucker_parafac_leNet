# LeNet on MNIST with Keras and Tensorflow in Python, using Tucker and PARAFAC decompositions on convolutional layers.

This is an implementation of a Skudarev Egor course work. This work based on these repositories:

https://github.com/JeanKossaifi/tensorly-notebooks/tree/master/02_tensor_decomposition

https://github.com/matthewrenze/lenet-on-mnist-with-keras-and-tensorflow-in-python/blob/master/MNIST-LeNet.py

It is trained to detect handwritten digits using the MNIST dataset. 

It was written in Python and uses Keras on top of Tensorflow by Yann Lee Cun.

The model correctly recognizes handwritten digits with approximately 98% accuracy.

There also created two models: model_tucker, where conv2D weights replaced with tucker decomposition, 
and model_parafac with PARAFAC decompositions on weigths.
