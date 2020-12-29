# imageclassification-cifar10
 Image Classification (AutoEncoder + Kmeans )
Use CIFAR10 dataset for this classification task. Following are the two approaches to the image classification task
that is implemented:
1. Supervised Learning Approach (SLA): Build a Neural Network Classifier (NN) with one
hidden layer to be trained and tested on CIFAR-10 dataset. Code from scratch in Python.
2. Unsupervised Learning Approach (USLA): USLA is a two step learning approach for image
classification.
(a) STEP 1: Extract image features using a Convolutional AutoEncoder (Conv-AE) for CIFAR10 dataset. Use an open-source neural-network library, Keras.
(b) STEP 2: Classify Auto-Encoded image features using K-Means clustering algorithm. You
can use sklearns.cluster.KMeans (off-the-shelf clustering libraries)
