I have deeveloped a Sign Language recognition system that uses a Convolutional Neural Network(CNN) trained on the Sign Language MNIST dataset.. 
This system recgonizes real time American Sign Language hand gestures from both test images and live camera feed.

I) OVERVIEW:
Dataset: Sign Language MNIST

Framework: TensorFlow / Keras

Language: Python

Model: Convolutional Neural Network (CNN)

Input: 28×28 grayscale images

Output: ASL alphabet letters 

Deployment: Real-time webcam prediction using OpenCV

II) MODEL ARCHITECTURE

The architecture of the model is:

Convolutional Layers -> Extract spatial features from hand images

Max Pooling Layers -> Reduce spatial dimensions and overfitting

Flatten Layer -> Converts 2D feature maps to 1D

Dense Layer -> Fully connected layer with ReLU activation

Dropout Layer - > Prevents overfitting

Output Layer -> Softmax activation for multi-class classification

III) STEPS:

1)Capture video using webcam

2)Define a Region of Interest (ROI)

3)Convert ROI to grayscale

4)Resize to 28×28

5)Normalize pixel values

6)Predict using trained CNN

7)Display predicted letter on screen

IV) TECHNOLOGIES USED:

Python

TensorFlow / Keras

OpenCV

NumPy

Pandas

Matplotlib

Seaborn

Scikit-learn

Softmax activation for multi-class classification

