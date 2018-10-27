# Capstone-project

# Unsupervised Image clustering 

## Project Overview
This project explores unsupervised learning as applied to images.
Images to us, humans, are naturally processed through our vision and brain systems. We learn
to recognize what things are without being explicitly told how to do so. To a computer, images
are a series of numbers representing the brightness of different colors in particular parts of the
image.
In traditional classification problems, we present the computer with images and labels
describing what the images represent. We then ask it to learn how to classify similar images by
looking at the ones we gave it. Using deep convolutional networks the computer detects
patterns in the images and relates them to the classification labels using fully connected neural
networks.
In unsupervised learning, the computer is asked to infer a pattern, structure, or relationship in
the data that we cannot see. One method of applying this is clustering where we ask the
computer to mark similar data points with the same label. Unsupervised clustering has been
used for image classification before.
We explore the notion that we can combine the powers of convolutional networks to represent
images in a more meaningful way for computers with the ability of unsupervised clustering
algorithms to group data points that are similar to each other in order to separate images of
different motorbikes, cars and planes.



## Problem Statement
Given a number of images of different motorbikes, cars and planes, label them such that all
images of the same category have the same label, and images of different category have
different labels.
To do this, we considered two different methods, both using convolutional neural networks.
Method one using autoencoders while other using pre trained models VGG16, VGG19. 
