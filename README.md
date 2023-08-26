# Scorpian's GAN-stract art

## About 

GAN-abstract art is a project developed by team scorpian which attempts to make an abstract art. The goal is to utilize the model for artists in idea generation when painting. Additionally, we wanted to see how a machine can be trained to recognize patterns in seemingly non-seqeuential work like abstract art. 

The way we approaced this was by creating two models- a generator and discriminator. The generator is a up-sampling convolutional neural network that based on smaller input, creates values that can be used to represent a real image. The discriminator is a convolutional neural network that goes through an image, recognizing the patterns to be able to discern which images are real or not. The discriminator is trained by providing it with real images  and random fake ones so evaluate to a value of 1 or 0 for each respectively. However, the generator is trained based on whether or not it can make the discrimator misclassify an image it creates to be real. Both are trained simultaneously, in a scenario where the discrimator has to adapt its parameters if it incorrectly recognizes a generated image as being real and the generator has to do the same if its image can not fool the discriminator. 


## Colab Notebook

A colab notebook has been provided to recreate the following experiment

'''

'''
