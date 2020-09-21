# CIFAR-10 Image Classification
The project attempts to classify 60000 images(50000 trainset and 10000 testset) from CIFAR-10 dataset into 10 classes: airplane ,automobile ,bird ,cat ,deer ,dog ,frog ,horse, ship or truck. This is done with the help of Convolutional Neural Netwroks(CNN).

The dataset can be previewed and downloaded from the link given below :

https://www.cs.toronto.edu/~kriz/cifar.html

Three Blocks have been employed in the classification task. Each block has a general form : CONV layers -> Relu -> Batch Normalisation followed by Max Pooling and Dropout. 
To enhance performance, Image Augmentation has been implemented. The model achieves 89.92 % Train accuracy and 89.78% Test accuracy.

The code is written in Python with the help of the popular deep learning framework Keras.
