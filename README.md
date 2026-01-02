# Handwritten_Character_Recognition
A python module that can take in live user alphanumeric character input and predict it.

It uses Keras/TensorFlow for building CNN(Convolutional Neural Network) that does the processing on the user input which is collected using a Graphical User Interface(using Tkinter) and the prediction is seen live using OpenCV.
The model uses the Kaggle A-Z datatset.

The model architecture is:

1) Conv2D + MaxPool: Extracts basic features.

2) Conv2D + MaxPool: Extracts complex patterns.

3) Dense Layers: Fully connected layers for classification.

4) Softmax Output: 26 nodes representing letters A through Z.
