# Neural-Network-Chihuahua-vs-muffin
Machine Learning project: Neural Network architectures to teach the AI to distinguish Chihuahua and muffin.

In this report we present our project about neural networks. We are asked
to use Keras, a Python library, to train different binary classifiers in order to
distinguish between images of muffins and Chihuahuas from this data set. In
particular, after the data preprocessing, i.e. converting images from JPG to
grayscale pixel values and scaling them down, we are asked to:
1. experiment with at least 3 different architectures and training hyperpa-
rameters;
2. use 5-fold cross validation to compute the risk estimates;
3. discuss the obtained results, especially the influence of the choices of hy-
perparameters and network architectures on the cross-validated risk esti-
mate.
Also, we have to use the zero-one loss to compute the cross-validated estimates.
Overall we follow the steps of the task trying to find the best model for our
data. We start with a base multilayer neural network that we improve until we
decide to move to a convolutional one that is more appropriate considering the
data we have. We manage to achieve a test accuracy of more than 90% thanks
to the final model.
3
