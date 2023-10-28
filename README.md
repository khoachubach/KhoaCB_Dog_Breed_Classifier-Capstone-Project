## KhoaCB_Dog_Breed_Classifier-Capstone-Project

# Overview 

In this project three different Convolutional Neural Networks (CNN) are trained to classified dog breeds. Additionally, the final model is also used to classify actors as dog breeds. (Of course this is just for entertaining.)

The three networks are:
-	Custom made network according to the popular guide from cs231n: https://cs231n.github.io/convolutional-networks/#layers
-	A newly trained VGG16
-	A pretrained ResNet50

The custom build network achieves just an accuracy of 4% while the VGG16 achieves 40% and the ResNet50 about 80%. This example clearly shows the benefit of using a pretrained model.

# How it works 

The plain workspace can be cloned from udacity

The images from the dogs and humans to train the networks can be downloaded from the following links and need to be placed in the “dogImages”-folder:
+ https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip
+ http://vis-www.cs.umass.edu/lfw/lfw.tgz

To train the networks udacity provided bootleneck features which can be downloaded from the following links and need to be placed in the “bottleneck_features”-folder:
+ https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/DogVGG16Data.npz
+ https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/DogResnet50Data.npz

# Personal Blog Post 

The process is presentet at medium blog post:
https://medium.com/@khoachubach/dog-breeds-classification-481245f5c941
My personal github also: https://github.com/khoachubach/KhoaCB_Dog_Breed_Classifier-Capstone-Project.git

# Review & References 

+ I'd recommend structuring the project writeup so that each rubric item is addressed in its own section (Project Overview, Problem Statement, Metrics etc.). Blog: https://medium.com/@khoachubach/dog-breeds-classification-481245f5c941
+ [Towards Data Science publication on Medium.](https://towardsdatascience.com/)
+ [Here is a blog post that explains when to use which classification or regression evaluation metrics.](https://towardsdatascience.com/20-popular-machine-learning-metrics-part-1-classification-regression-evaluation-metrics-1ca3e282a2ce)
+ You could have tried and specified some preprocessing steps for e.g. transforming the images before passing it to model for training and prediction. [This resource](https://keras.io/api/preprocessing/image/) on how to do it in Keras can be helpful to you if you choose to explore further in that direction.
+ You can practise to follow Google’s Python Coding style
+ This lady has shared some [good tips on how to write a great README for your GitHub project](https://bulldogjob.com/news/449-how-to-write-a-%20good-readme-for-your-github-project). 
