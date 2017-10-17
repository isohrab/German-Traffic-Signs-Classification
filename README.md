# German-Traffic-Signs-Classification
A Convolution Neural Networks implemented with Tensorflow

The images in this dataset have different sizes. Also, images divided into different folders.

In this model, I used 3 convolution layers and followed with 3 fully connected layers. By adding batch normalization after each layer in fully connected layer, I got a better result by appx ~ 1%. Of course this is a complex model which can overfit the data, but by using dropout in fully connected layers, I could prevent overfitting.

You can download dataset from following [link](http://benchmark.ini.rub.de/?section=gtsrb&subsection=dataset#Downloads)
