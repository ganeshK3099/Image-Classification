# Image-Classification
This is a project for image classification using a Convolutional Neural Network (CNN) with TensorFlow and Keras. The goal of this project is to classify images of different  products.

## Dataset
The dataset used in this project consists of images of five different types of shampoos and hair care products:
<br>8xShampoo
<br>saslic
<br>wow
<br>headnshoulders
<br>mamaearth
<br>The images are divided into training and validation sets

# Model Architecture
The CNN model used for image classification consists of the following layers:
<br>Conv2D layer with 32 filters and 3x3 kernel size
MaxPooling2D layer with 2x2 pool size<br>
Conv2D layer with 64 filters and 3x3 kernel size<br>
MaxPooling2D layer with 2x2 pool size<br>
Conv2D layer with 128 filters and 3x3 kernel size<br>
MaxPooling2D layer with 2x2 pool size<br>
Flatten layer<br>
Dense layer with 128 units and ReLU activation<br>
Dense layer with 5 units and softmax activation<br>
