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

# The model was compiled using the following hyperparameters:
Optimizer: Adam<br>
Loss function: Categorical Cross-Entropy<br>
Metrics: Accuracy<br>


# Training and Evaluation
The model was trained on the training set for 10 epochs with a batch size of 32. The validation set was used for validation during training. After training, the model was evaluated on the testing set to calculate the test loss and test accuracy.<br>

# Predictions
The trained model can be used to make predictions on new images. The "predict" function can be used to generate the probability distribution for each class, and the argmax function can be used to find the class with the highest probability.<br>


# Requirements
The following packages are required to run the code in this project:<br>

tensorflow<br>
numpy<br>
matplotlib<br>
pillow<br>
These can be installed using the following command:<br>
pip install tensorflow numpy matplotlib pillow<br>

# Usage
The complete code is provided in .ipynb file<br>

# License
This project is licensed under the MIT License.
