# Sentiment_Analysis

uses a CNN model with sequential model object and add layers to it. Here's a breakdown of the model architecture:

1.Convolutional layer with 16 filters of size 3x3, using ReLU activation and a stride of 1. The input_shape specifies the shape of the input image as (256, 256, 3).
2.Max pooling layer with default pool size (2x2) and stride.
3.Convolutional layer with 32 filters of size 3x3, using ReLU activation and a stride of 1.
4.Max pooling layer with default pool size (2x2) and stride.
5.Convolutional layer with 16 filters of size 3x3, using ReLU activation and a stride of 1.
6.Max pooling layer with default pool size (2x2) and stride.
7.Flatten layer to convert the 2D feature maps to a 1D vector.
8.Fully connected (Dense) layer with 256 units and ReLU activation.
9.Fully connected (Dense) layer with 1 unit and sigmoid activation for binary classification.

The final classification is for either happy or sad
