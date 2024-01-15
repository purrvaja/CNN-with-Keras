# Image Recognition with CNN and Keras
This project demonstrates image classification using Convolutional Neural Networks (CNNs) and the Keras deep learning library. A CNN model has been applied to the popular Fashion MNIST dataset to recognize 10 different clothing types from images.


**Project Objective:**

* Build and train a CNN model on the Fashion MNIST dataset to accurately classify clothing images.
* Gain practical experience with image classification using Keras and CNNs.

  
**Dataset:**

Fashion MNIST: Dataset of grayscale images categorized into 10 classes of clothing (t-shirt, dress, etc.).
Contains 60,000 training images and 10,000 testing images.


**Model Architecture:**

* Convolutional layers are used to extract features from images.
* Pooling layers are used to reduce spatial dimensions.
* Dense layers are used to perform classifications.
* ReLU activation function is used in intermediate layers for non-linear learning and efficient gradient propagation.
* Softmax activation function is applied to the output layer to produce a probability distribution indicating the likelihood of each class for a given image.

**Results:**

Achieved 0.8673 accuracy on the test set.
This might be improved further with hyperparameter tuning. 
