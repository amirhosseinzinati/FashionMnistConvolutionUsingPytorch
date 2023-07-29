# Convolutional Neural Network for FashionMNIST Dataset using PyTorch

This project aims to build a Convolutional Neural Network (CNN) model using PyTorch to classify images in the FashionMNIST dataset. The model achieves a classification accuracy of 91% on the test set.

Dataset
The FashionMNIST dataset consists of 70,000 grayscale images of size 28x28 pixels, divided into 60,000 training images and 10,000 test images. The images belong to 10 different categories of clothing items, including t-shirts, trousers, dresses, and shoes. The dataset is commonly used for benchmarking computer vision models.

Architecture
The CNN model consists of two convolutional layers followed by two fully connected layers. Each convolutional layer is followed by a max pooling layer. The output of the second fully connected layer is fed into a softmax function to produce class probabilities.

The model was trained on a GPU using the Adam optimizer and cross-entropy loss function. The learning rate was set to 0.001 and the batch size was 64.

Results
The model achieved an accuracy of 91% on the test set after training for 10 epochs.

Conclusion
In conclusion, we have built a CNN model using PyTorch to classify images in the FashionMNIST dataset. The model achieved a classification accuracy of 91% on the test set, demonstrating the effectiveness of the CNN architecture for image classification tasks.
