# Image-Classification-Model-of-the-Apparels

Clothing serves for much more than just protection and covering. It is a means of communication to reflect social status, lifestyles, or even fashion sense. Therefore, a huge amount and various styles of clothes have been produced to satisfy people’s different taste.

Fashion-MNIST is a dataset of Zalando's images—consisting of a training set of 60,000 examples and a test set of 10,000 examples. Each example is a 28x28 grayscale image, associated with a label from 10 classes. We intend Fashion-MNIST to serve as a direct drop-in replacement for the original MNIST dataset for benchmarking machine learning algorithms. It shares the same image size and structure of training and testing splits.

The objective of our project is to classify clothes by purely scanning and analyzing clothes pictures. Furthermore, we will compare our accuracy level among different algorithms we will be using.

**Labels**

0: 'T - shirt / top', 1: 'Trouser', 2: 'Pullover', 3: 'Dress', 4: 'Coat', 5: 'Sandal', 6: 'Shirt', 7: 'Sneaker', 8: 'Bag', 9: 'Ankleboot'

Each example is a 28x28 grayscale image, associated with a label from 10 classes

The Fashion-MNIST data is intended to be a direct drop-in replacement for the old MNIST handwritten digits data, since there were several issues with the handwritten digits. For example, it was possible to correctly distinguish between several digits, by simply looking at a few pixels. Even with linear classifiers it was possible to achieve high classification accuracy. The Fashion-MNIST data promises to be more diverse so that machine learning (ML) algorithms have to learn more advanced features in order to be able to separate the individual classes reliably.


**Conclusion**

Based on all models’ performance, the convolutional network gives best performance on test set, and it doesn’t tend to overfit dataset by using dropout regularization method. It is surprising that the linear classifiers have high accuracies in test set. It may be because we have reshaped all the input images to the same shape and all the images are clean and well organized.
Although CNN outperforms linear classifier in our dataset, it takes much longer time to train the model. When we get a large dataset, it will take a lot of time to train a good CNN model.
