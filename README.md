# CarClassificationCNN
Application of data augmentation to a set of car images in order to train a simple CNN to classify car images according to their respective brands; Audi, Lamborghini or Mercedes

This repository contains 2 ipynb files. Both are meant to perform car brand classification. 

The first attemp at this challenge used transfer learning methods using the Resnet50 model, however, due to the lack of training images, this model did not perform very well; severe overfitting.

The second attempt applied the same data augmentation technique to better fit the small input training set to a simpler CNN and performs better thant the ResNet model.
