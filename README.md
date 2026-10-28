# Indoor_Fire_Detector

This code designs and trains a convolutional neural network (CNN) to classify images as "Fire" or "No-Fire". It uses TensorFlow and Keras and is intended to support image-based fire detection research.



Workflow:
- Resizes images to 224 × 224 pixels and normalizes pixel values.
- Applies data augmentation to training images, including rotation, zoom, shifting, shearing, brightness changes, and horizontal flipping.
- Uses class weights to address the imbalance between fire and no-fire images.
- Trains a CNN with the Adam optimizer and binary cross-entropy loss.
- Evaluates predictions with a classification report and confusion matrix.
- Saves the model in Keras, SavedModel, and TensorFlow Lite formats.
