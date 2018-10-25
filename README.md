# Udacity dog breed project
Build a pipeline to process real-world, user-supplied images.  
Given an image of a dog, the algorithm will identify an estimate of the canine’s breed.
If supplied an image of a human face, the code will identify the resembling dog breed.


## Detect Humans
Assess the Human Face Detector
The submission returns the percentage of the first 100 images in the dog and human face datasets that include a detected, human face.

## Detect Dogs
Use a pre-trained VGG16 Net to find the predicted class for a given image: `dog_detector` function returns `True` if a dog is detected in an image and `False` if not.

Assess the Dog Detector
The submission returns the percentage of the first 100 images in the dog and human face datasets that include a detected dog.

## CNN to Classify Dog Breeds from Scratch
CNN architecture of trained model attains at least 10% accuracy on the test set.

## CNN to Classify Dog Breeds Using Transfer Learning
Model architecture that uses part of a pre-trained model with accuracy on the test set of 60% or greater.
