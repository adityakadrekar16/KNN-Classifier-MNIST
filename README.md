## K-Nearest Neighbor Classifier from scratch

Implementation of K-Nearest Neighbors classifier from scratch for image classification on MNIST dataset.
No existing sklearn packages were used for writing the knn code.

### Dataset:
In MNIST dataset, each sample is a picture of a hand written digit. Each sample includes 28x28 grey-scale pixel values as features and a categorical class label out of 0-9. For more details, please refer to Dr. Yann Lecun’s page (http://yann.lecun.com/exdb/mnist/). The dataset has been imported using sklearn.dataset package.

### Implementation
I have implemented the classifier with the L2-norm (Euclidean distance) as the distance measurement between samples. In the original data set, the first 60,000 samples are for training, and the remaining 10,000 samples are for testing. In this implementation, I have used the first 6,000 samples from the original training set for training KNN, and the first 1,000 from the original test set for testing KNN.






