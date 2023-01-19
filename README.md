### Using CNN network architecture to solve a classification problem and to identify the handwritten digits ranging from 0-9 on an MNIST dataset.

### About MNIST Dataset and its Importance
The MNIST database (Modified National Institute of Standards and Technology database) is a large database of handwritten digits that is commonly used for training various image processing systems. The database is also widely used for training and testing in the field of machine learning.

![alt text](https://upload.wikimedia.org/wikipedia/commons/thumb/2/27/MnistExamples.png/320px-MnistExamples.png)

### In Summary:
The MNIST dataset consists of 70,000 28x28 black-and-white images of handwritten digits extracted from two NIST databases. There are 60,000 images in the training dataset and 10,000 images in the validation dataset, one class per digit so a total of 10 classes, with 7,000 images (6,000 train images and 1,000 test images) per class.

1. In this Case Study, we have tried rebuilding the famous CNN architectures, LeNet and AlexNet.
2. We see that in these algorithms, the number of parameters that are required to train are extremely huge.
3. The LeNet architecture when compared to AlexNet architecture has a lesser number of convolution and pooling layers.
4. We have used the concept of early stopping in order to save up on running unnecessary resources for the same set of accuracy.
5. We also see that the number of epochs that we used for LeNet were 10 with a batch size
of 120 produced an accuracy of almost 99%
6. In case of AlexNet, the epochs were 10 and the batch size of 64 was used to obtain an accuracy of 99% again.
7. Further, we have also plotted the Training-Validation Accuracy and Losses for both of these networks. We see that as the number of epochs increases the    training loss increases and the training accuracy increases. When talking about the number of epoch increases in case of validation, we see that for a      few epochs, the loss seems to be lower than the previous epochs and then increase later on before appearing to converge to a constant value.
8. Both the graphs for AlexNet and LeNet appear to be similar.

