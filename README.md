# CNN_for_bird_classification
Convolutional Neural Network to classify images of birds into Cardinal and Indigo. Only TensorFlow operations are used to read image files, and build CNN.
# Dependencies
TensorFlow 1.0, Numpy
# Operations
tf.layers, tf.image, tf.gfile, tf.losses
# CNN Architecture
2 Convolutional layers with ReLU activation, 2 Max Pooling Layers, 1 Fully Connected Layer with Softmax Activation
# Training
Training data: 72 images,
Validation data: 24 images,
Testing data: 4 images
# Classification - 3 Classes
0: Cardinal; 1: Indigo; 2: None of these
# Dataset
Source: CUB-200 available at http://www.vision.caltech.edu/visipedia/CUB-200.html
